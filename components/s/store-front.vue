<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-699-bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r-699-bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:store-front" /></template>
