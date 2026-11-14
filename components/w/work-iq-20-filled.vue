<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f7b3n_bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-20-filled" /></template>
<style>
.f7b3n_bls {
  fill: currentColor;
  d: path("M11.5 13a.5.5 0 0 1 .5.5v5a.5.5 0 1 1-1 0v-5a.5.5 0 0 1 .5-.5m4.5 0a3 3 0 0 1 3 3c0 .647-.208 1.246-.557 1.736l.41.41a.5.5 0 0 1-.707.707l-.41-.41c-.49.35-1.088.557-1.736.557a3 3 0 1 1 0-6m-2.75-9.207a2 2 0 0 1 1.977-.013l1.273.735A3 3 0 0 1 18 7.113v5.423A4 4 0 0 0 16 12a4 4 0 0 0-3.008 1.363A1.499 1.499 0 0 0 10 13.5v5q.001.14.025.272a3 3 0 0 1-1.525-.401L7 17.506a2 2 0 0 1-1-1.733v-6.64a2 2 0 0 1 1-1.732zM16 14a2 2 0 0 0 0 4c.37 0 .716-.104 1.014-.28l-.867-.867a.5.5 0 0 1 .707-.707l.867.867c.175-.297.279-.643.279-1.013a2 2 0 0 0-2-2M8.5 1.629a3 3 0 0 1 3 0l1.813 1.046a3 3 0 0 0-.563.252L6.5 6.536A3 3 0 0 0 5 9.133v6.64q0 .314.063.614L3.5 15.485A3 3 0 0 1 2 12.886V7.113a3 3 0 0 1 1.5-2.598z");
}

</style>
