<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>Hello World</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <img alt="Vue logo" src="/src/assets/logo.png" />
            <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
        </ion-content>
    </ion-page>
</template>

<script lang="ts" setup>
    import HelloWorld from '/src/components/HelloWorld.vue'
    import { IonPage, IonContent, IonHeader, IonToolbar, IonTitle } from '@ionic/vue';
</script>