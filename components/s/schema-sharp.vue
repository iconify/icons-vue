<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcifpybem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:schema-sharp" /></template>
<style>
.fcifpybem {
  fill: currentColor;
  d: path("M4.885 22.116v-4.232H7v-3.768H4.884V9.885H7v-3.77H4.884v-4.23h5.232v4.23H8v3.77h2.116V11.5h4.769V9.884h5.23v4.232h-5.23V12.5h-4.77v1.616H8v3.769h2.116v4.23z");
}

</style>
