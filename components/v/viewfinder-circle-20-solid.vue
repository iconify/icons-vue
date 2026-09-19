<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll6-iwbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ll6-iwbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:viewfinder-circle-20-solid" /></template>
