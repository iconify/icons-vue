<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc4xqrbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:precision-manufacturing-sharp" /></template>
<style>
.oc4xqrbty {
  fill: currentColor;
  d: path("M3.975 21v-3h3.1l-2.55-8.35q-.675-.375-1.112-1.1T2.975 7q0-1.25.875-2.125T5.975 4q.975 0 1.738.563T8.775 6h3.2V4h1.475l.325.4L16 2.3l5.2 2.45l-.6 1.3l-4.275-1.95l-2.35 2.2v1.4l2.35 2.15L20.65 7.9l.6 1.3L16 11.7l-2.225-2.1l-.4.4h-1.4V8h-3.2q-.075.2-.162.375t-.238.375l5 9.25h3.6v3zM6.688 7.712q.287-.287.287-.712t-.287-.712T5.975 6t-.712.288T4.975 7t.288.713t.712.287t.713-.288");
}

</style>
