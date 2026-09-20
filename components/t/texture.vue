<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyjnvwbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:texture" /></template>
<style>
.tyjnvwbyp {
  fill: currentColor;
  d: path("M4.708 20q-.245-.08-.436-.272q-.191-.191-.272-.436L19.292 4q.256.087.439.272t.275.436zM4 13.527v-1.415L12.111 4h1.416zm0-7.18v-.731q0-.691.463-1.153T5.616 4h.73zM17.654 20L20 17.654v.73q0 .691-.462 1.153T18.384 20zm-7.181 0L20 10.473v1.416L11.889 20z");
}

</style>
