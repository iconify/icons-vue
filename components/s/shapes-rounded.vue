<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndp70_xnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shapes-rounded" /></template>
<style>
.ndp70_xnk {
  fill: currentColor;
  d: path("M4.98 13.482q-1.75-1.75-1.75-4.251T4.98 4.98t4.25-1.75t4.252 1.75t1.749 4.25t-1.75 4.252t-4.25 1.749t-4.251-1.75m5.405 7.288q-.672 0-1.144-.472t-.472-1.143v-.477q0-.292.195-.487q.195-.196.494-.215q1.74-.077 3.24-.692q1.5-.616 2.735-1.85q1.234-1.235 1.85-2.735q.615-1.5.692-3.24q.02-.298.215-.493q.195-.196.487-.196h.477q.671 0 1.143.472q.472.473.472 1.144v8.769q0 .671-.472 1.143t-1.143.472z");
}

</style>
