<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gorhfqwsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-disabled-sharp" /></template>
<style>
.gorhfqwsh {
  fill: currentColor;
  d: path("M19.833 21.26L17 18.427V20H7v-4H3.577V8.616h3.612L2.74 4.167l.713-.713l17.092 17.092zM8 19h8v-1.573l-2.965-2.965H8zm10.812-3l-7.385-7.384h8.996V16zM17 7.846h-6.342l-3.231-3.23H17zm.616 4.27q.425 0 .712-.288t.288-.712t-.288-.713t-.712-.288t-.713.288t-.287.713t.287.712t.713.288");
}

</style>
