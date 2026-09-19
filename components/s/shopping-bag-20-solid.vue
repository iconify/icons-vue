<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_ebj2hts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u_ebj2hts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shopping-bag-20-solid" /></template>
