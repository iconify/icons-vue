<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-bciz-_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-bciz-_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tshirt" /></template>
