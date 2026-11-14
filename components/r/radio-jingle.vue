<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj4r_vp9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:radio-jingle" /></template>
<style>
.cj4r_vp9i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 14.753q-.771-.504-1.75-.504q-1.347 0-2.298.952q-.952.953-.952 2.299t.952 2.299q.951.952 2.298.952t2.298-.952q.952-.953.952-2.299V9.609l8-1.685v4.66q-.708-.334-1.75-.334q-3.25 0-3.25 3.25t3.25 3.25t3.25-3.25v-12q0-.078-.016-.155q-.031-.145-.115-.269q-.084-.123-.209-.204q-.125-.082-.272-.109q-.147-.028-.293.003l-9.5 2q-.062.013-.122.037q-.059.024-.114.057t-.103.076t-.088.091q-.041.05-.072.106t-.053.116q-.021.061-.032.124T8.75 5.5zm1.5-6.677V6.109l8-1.685v1.967z");
}

</style>
