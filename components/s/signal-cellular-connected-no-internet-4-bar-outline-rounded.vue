<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ork-86ujw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-connected-no-internet-4-bar-outline-rounded" /></template>
<style>
.ork-86ujw {
  fill: currentColor;
  d: path("M3.7 20.3L20.275 3.725q.5-.5 1.113-.237t.612.937V8h-1q-1.25 0-2.125.875T18 11v11H4.4q-.65 0-.913-.612T3.7 20.3m16.588 1.413Q20 21.425 20 21t.288-.712T21 20t.713.288T22 21t-.288.713T21 22t-.712-.288M20 17v-6q0-.425.288-.712T21 10t.713.288T22 11v6.025q0 .425-.288.7T21 18t-.712-.288T20 17");
}

</style>
