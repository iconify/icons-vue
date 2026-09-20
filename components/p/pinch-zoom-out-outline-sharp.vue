<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ksupb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pinch-zoom-out-outline-sharp" /></template>
<style>
.t5ksupb-a {
  fill: currentColor;
  d: path("M1.616 12V7.616H2.5v2.873l3.264-3.264l.627.627l-3.264 3.264H6V12zm6.236-5.61l-.627-.626L10.489 2.5H7.616v-.884H12V6h-.885V3.127zm5.185 15.38l-5.668-5.654l.922-.895l3.44.858v-8.81h1v10.152l-3.637-.982l4.35 4.33h6.787v-7h1v8zm1.52-6.5v-4.5h1v4.5zm2.847 0v-3.5h1v3.5zm-.962 2.634");
}

</style>
