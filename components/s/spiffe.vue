<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h02ds3bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":358.28,"height":358.28,"left":0.11,"top":1.86};
const content = `<path clip-rule="evenodd" class="h02ds3bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:spiffe" /></template>
