<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slhbl4b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-wrench-sharp" /></template>
<style>
.slhbl4b1q {
  fill: currentColor;
  d: path("M12.713 5.713Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288M5 23V1h14v5.1h1v4.8h-1v1.7q-.575-.275-1.2-.437T16.5 12q-2.275 0-3.887 1.613T11 17.5t1.613 3.888T16.5 23zm14.875 0l-2.2-2.2q-.275.125-.575.163t-.6.037q-1.475 0-2.488-1.012T13 17.525q0-.45.113-.875t.312-.8l2.375 2.375l1.4-1.425l-2.375-2.35q.375-.2.8-.312t.875-.113q1.45 0 2.475 1.013T20 17.525q0 .3-.05.6t-.175.575L22 20.9z");
}

</style>
