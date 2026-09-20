<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_xb8ddtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:settings-input-component" /></template>
<style>
.d_xb8ddtt {
  fill: currentColor;
  d: path("M3.904 22v-4.43q-.817-.224-1.36-.852Q2 16.091 2 15.212v-2.346h4.808v2.346q0 .879-.543 1.506q-.544.628-1.361.851V22zm7.596 0v-4.43q-.817-.224-1.36-.852q-.544-.627-.544-1.506v-2.346h4.808v2.346q0 .879-.543 1.506q-.544.628-1.361.851V22zm7.596 0v-4.43q-.817-.224-1.36-.852q-.544-.627-.544-1.506v-2.346H22v2.346q0 .879-.543 1.506q-.544.628-1.36.851V22zM2 11.866V6.173h1.904V2.5q0-.213.144-.356T4.405 2t.356.144t.143.356v3.673h1.904v5.693zm7.596 0V6.173H11.5V2.5q0-.213.144-.356T12.001 2t.356.144t.143.356v3.673h1.904v5.693zm7.596 0V6.173h1.904V2.5q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356v3.673H22v5.693z");
}

</style>
