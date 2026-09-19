<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j7qebeb1c"/><path class="ka6uajjcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-tv" /></template>
<style>
.j7qebeb1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5 18.179l23.422-7.961c4.571-1.94 6.342.256 2.714 5.158");
}

.ka6uajjcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.642 13.882s1.13 18.829.535 21.716m7.948-16.11c1.312 1.332 6.857 18.996 6.857 18.996c.01-3.917 7.651-23.566 10.018-25.35");
}

</style>
