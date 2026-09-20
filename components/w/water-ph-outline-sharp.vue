<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1p1c2baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-ph-outline-sharp" /></template>
<style>
.q1p1c2baw {
  fill: currentColor;
  d: path("M9.423 20.97q-2.78-.216-4.602-2.231Q3 16.723 3 13.8q0-2.154 1.738-4.765T10 3.308q3.429 3.04 5.166 5.583T17 13.57v.046h-1v-.046q-.096-1.806-1.599-4.048T10 4.65Q7.025 7.375 5.513 9.675T4 13.8q0 2.54 1.525 4.244t3.898 1.92zm2 .03v-5.384h4.385v3.461h-3.5V21zm6.077 0v-5.384h.885v2H21v-2h.885V21H21v-2.5h-2.616V21zm-5.192-2.808h2.615V16.54h-2.615z");
}

</style>
