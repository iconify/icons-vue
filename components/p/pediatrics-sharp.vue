<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr5-0ybma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pediatrics-sharp" /></template>
<style>
.fr5-0ybma {
  fill: currentColor;
  d: path("M7 7V5h4V2h2v3h4v2zm2 15q-.825 0-1.412-.587T7 20v-2h5v-2H7v-2h5v-2H7v-1q0-1.25.875-2.125T10 8h4q1.25 0 2.125.875T17 11v9q0 .825-.587 1.413T15 22z");
}

</style>
