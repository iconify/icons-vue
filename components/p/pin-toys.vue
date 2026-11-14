<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noo-jj-we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-toys" /></template>
<style>
.noo-jj-we {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.47 6.47l4-4q.105-.106.243-.163T7 2.25h14q.149 0 .287.057t.243.163q.028.027.052.057q.082.101.125.222q.043.122.043.251v14q0 .149-.057.287t-.163.243l-4 4q-.048.048-.104.087t-.118.067t-.128.044t-.134.021t-.136-.004t-.133-.029t-.125-.052t-.114-.073q-.439.159-1.038.159h-11q-2.25 0-2.25-2.25v-11q0-.599.159-1.038q-.042-.054-.073-.114q-.032-.06-.052-.125t-.029-.133t-.004-.136t.021-.134t.044-.128t.067-.118t.087-.104m16.719-2.72H7.311l-2.5 2.5H15.5q.595 0 1.032.157zm-1.596 3.718q.157.437.157 1.032v10.689l2.5-2.5V4.811zM6.25 14q0 3.75 3.75 3.75T13.75 14T10 10.25T6.25 14");
}

</style>
