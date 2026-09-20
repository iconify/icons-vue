<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na_y7ubzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mimo-disconnect" /></template>
<style>
.na_y7ubzg {
  fill: currentColor;
  d: path("m4.425 4.04l-.192 1.224l-2.456-2.456l.708-.708l18.684 18.685l-.707.707l-3.8-3.8h-.623l.769.77V20H7.192v-1.538l.77-.77H4.616q-.691 0-1.153-.462T3 16.077V5.616q0-.714.463-1.145t.962-.43M20.45 17.235L7.158 4h12.227q.69 0 1.153.463T21 5.616v10.461q0 .439-.16.708q-.161.269-.39.45");
}

</style>
