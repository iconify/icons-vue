<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvic11bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-laser-pointer-sharp" /></template>
<style>
.kvic11bdf {
  fill: currentColor;
  d: path("M7.23 20.289q-.73-.731-.73-1.77t.73-1.769T9 16.02t1.77.73t.73 1.77t-.73 1.769t-1.77.73t-1.77-.73m6.034-2.745q-.189-.875-.718-1.598t-1.29-1.137l3.246-3.213H6.4q-.608 0-1.004-.434Q5 10.727 5 10.1q0-.384.195-.697t.505-.53l10.996-6.852q.277-.16.585-.08t.467.357q.16.258.09.563t-.322.464L8.058 9.5H17.6q.589 0 .994.406T19 10.9q0 .354-.074.705t-.322.599z");
}

</style>
