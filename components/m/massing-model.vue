<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoizc_b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:massing-model" /></template>
<style>
.hoizc_b4p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.47 6.47l3-3q.105-.106.243-.163T7 3.25h7q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.25H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v7.5q0 .149-.057.287t-.163.243l-3 3q-.048.048-.104.087t-.118.067t-.128.044t-.134.021t-.136-.004t-.133-.029t-.125-.052t-.114-.073q-.439.159-1.038.159h-4q-.951 0-1.5-.402q-.549.402-1.5.402h-4q-2.25 0-2.25-2.25V8.5q0-.599.159-1.038q-.042-.054-.073-.114q-.032-.06-.052-.125t-.029-.133t-.004-.136t.021-.134t.044-.128t.067-.118t.087-.104m9.78 3.219V5.811l-1.657 1.657q.157.437.157 1.032v2.689zM12.189 4.75H7.311l-1.5 1.5H9.5q.595 0 1.032.157zm4.311 7.5q.595 0 1.032.157l1.657-1.657h-4.878l-1.5 1.5zm2.25 6.439l1.5-1.5v-5.378l-1.657 1.657q.157.437.157 1.032z");
}

</style>
