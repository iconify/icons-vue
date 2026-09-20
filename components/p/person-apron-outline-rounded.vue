<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvul4d3ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-apron-outline-rounded" /></template>
<style>
.bvul4d3ju {
  fill: currentColor;
  d: path("M9.877 10.508Q9 9.63 9 8.385t.877-2.123T12 5.385t2.123.877T15 8.385t-.877 2.123t-2.123.877t-2.123-.877M5 17.577v-.6q0-.637.367-1.171t.964-.833q1.346-.635 2.77-.996t2.903-.362t2.899.362t2.766.996q.597.298.964.833T19 16.977v.6q0 .44-.299.74q-.299.299-.74.299H6.04q-.441 0-.74-.3q-.3-.299-.3-.739m8.413-7.78Q14 9.21 14 8.385t-.587-1.413T12 6.385t-1.412.587T10 8.385t.588 1.412t1.412.588t1.413-.588m2.01 5.345v2.474H18v-.647q0-.371-.24-.653t-.568-.466q-.427-.22-.872-.391t-.897-.317m-5.846-.255v1.229h4.846v-1.23q-.596-.138-1.207-.204q-.61-.066-1.22-.066q-.612 0-1.217.066t-1.202.205M6 17.616h2.577v-2.474q-.452.145-.897.317t-.872.391q-.327.183-.567.466q-.241.282-.241.653zm9.423 0H8.577zM12 8.385");
}

</style>
