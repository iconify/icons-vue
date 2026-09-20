<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urdk39bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unknown-document-sharp" /></template>
<style>
.urdk39bxq {
  fill: currentColor;
  d: path("M16.684 19.38q.158-.159.158-.376q0-.218-.158-.376q-.159-.159-.376-.159t-.376.159t-.159.376t.159.376t.376.159t.376-.16m-.75-1.625h.747v-.173q0-.294.15-.478t.35-.384q.35-.3.55-.613t.2-.775q0-.687-.447-1.124q-.446-.438-1.176-.438q-.537 0-1 .338t-.662.874l.685.273q.113-.3.37-.525t.607-.225q.413 0 .645.207q.232.206.232.62q0 .294-.17.491q-.169.197-.369.397q-.15.15-.293.32q-.144.169-.268.33q-.075.131-.113.29q-.037.16-.037.322zm-2.462 1.774q-1.164-1.164-1.164-2.836q0-1.67 1.164-2.835t2.836-1.165q1.67 0 2.835 1.165t1.165 2.835t-1.165 2.836t-2.835 1.164t-2.836-1.164M13 8h4l-4-4l4 4l-4-4zM4 21V3h9.5L18 7.5v3.03q-.423-.13-.836-.176q-.414-.046-.856-.046q-1.445 0-2.688.585T11.504 12.5H7.5v1h3.29q-.378.667-.605 1.427T9.94 16.5H7.5v1h2.479q.137.971.546 1.865T11.605 21z");
}

</style>
