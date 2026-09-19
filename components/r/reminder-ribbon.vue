<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o6311g7ix"/><path class="t7kmu08cw"/><path class="mpgqgjsgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:reminder-ribbon" /></template>
<style>
.mpgqgjsgh {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M29.8 2.1S12 1.2 12 18.8S43.2 62 43.2 62l4.9-11.1S-6.2 6.4 29.8 2.1");
}

.o6311g7ix {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M32.1 2S19.4 2 17.4 6.9c-.8 1.9-.1 7.6.1 9.4c1.7-3.2 7.5-5.6 14.3-5.6c7.2 0 13.2 2.6 14.5 6.1h.3V7.1c0-2.4-6.3-5.1-14.5-5.1");
}

.t7kmu08cw {
  fill: var(--svg-color--ff5760, #ff5760);
  d: path("M34.1 2.1S52 1.2 52 18.8S20.8 62 20.8 62l-4.9-11.1c0-.1 54.1-44.5 18.2-48.8");
}

</style>
