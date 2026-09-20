<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg0hjcyzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:roller-shades" /></template>
<style>
.mg0hjcyzy {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm3-1h12v-6.404h-5.5v2.646q.292.154.464.414q.17.26.17.594q0 .47-.333.802t-.805.333t-.8-.333t-.33-.802q0-.334.17-.591q.172-.257.464-.411v-2.652H6z");
}

</style>
