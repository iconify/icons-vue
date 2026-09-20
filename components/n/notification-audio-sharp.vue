<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-eawfv7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:notification-audio-sharp" /></template>
<style>
.n-eawfv7y {
  fill: currentColor;
  d: path("M12 22q-.825 0-1.412-.587T10 20h4q0 .825-.587 1.413T12 22m8-3H4v-2h2v-7q0-2.075 1.25-3.687T10.5 4.2V2h3v2.2q.575.15 1.1.4t1 .6q-1.575.45-2.588 1.763T12 10q0 2.075 1.463 3.538T17 15q.275 0 .513-.025T18 14.9V17h2zm-3.75-6V7h1.5v6zm-2.75-1.5v-3H15v3zm5.5 0v-3h1.5v3z");
}

</style>
