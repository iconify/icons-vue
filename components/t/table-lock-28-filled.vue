<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x5oya-b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-lock-28-filled" /></template>
<style>
.x5oya-b0c {
  fill: currentColor;
  d: path("M3 6.75A3.75 3.75 0 0 1 6.75 3H9.5v6.5H3zM3 11v6h6.5v-6zm0 7.5v2.75A3.75 3.75 0 0 0 6.75 25H9.5v-6.5zm8 6.5h4v-5c0-.546.146-1.059.401-1.5H11zm14-14v4.062a4 4 0 0 0-6.5-.708V11zm0-1.5V6.75A3.75 3.75 0 0 0 21.25 3H18.5v6.5zM17 3h-6v6.5h6zm0 8v6h-6v-6zm1.5 7H18a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h7a2 2 0 0 0 2-2v-5a2 2 0 0 0-2-2h-.5v-1a3 3 0 1 0-6 0zm1.5-1a1.5 1.5 0 0 1 3 0v1h-3zm3 5.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
