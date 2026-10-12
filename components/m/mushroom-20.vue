<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prt_k_bso.css';
import '../../css/k/koi711brx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prt_k_bso"/><path class="koi711brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mushroom-20" /></template>
