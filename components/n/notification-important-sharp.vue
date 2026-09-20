<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk_2npbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:notification-important-sharp" /></template>
<style>
.uk_2npbvr {
  fill: currentColor;
  d: path("M4 19v-2h2v-7q0-2.075 1.25-3.687T10.5 4.2V2h3v2.2q2 .5 3.25 2.113T18 10v7h2v2zm8 3q-.825 0-1.412-.587T10 20h4q0 .825-.587 1.413T12 22m-1-9h2V8h-2zm1 3q.425 0 .713-.288T13 15t-.288-.712T12 14t-.712.288T11 15t.288.713T12 16");
}

</style>
