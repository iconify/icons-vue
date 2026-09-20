<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9-j_ob0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:schedule-rounded" /></template>
<style>
.d9-j_ob0j {
  fill: currentColor;
  d: path("M13 11.6V8q0-.425-.288-.712T12 7t-.712.288T11 8v3.975q0 .2.075.388t.225.337l3.3 3.3q.275.275.7.275T16 16t.275-.7t-.275-.7zM12 22q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
