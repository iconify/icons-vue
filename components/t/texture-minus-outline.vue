<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncdrqmb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:texture-minus-outline" /></template>
<style>
.ncdrqmb-t {
  fill: currentColor;
  d: path("M4.708 20q-.245-.08-.436-.272q-.191-.191-.272-.436L19.292 4q.256.087.439.272t.275.436zm5.765 0l1.143-1.142V20zM14 17.616v-1h7v1zM4 13.527v-1.415L12.111 4h1.416zm12.242.704L20 10.473v1.416l-2.342 2.342zM4 6.346v-.73q0-.691.463-1.153T5.616 4h.73z");
}

</style>
