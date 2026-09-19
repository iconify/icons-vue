<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urjfcxktu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="urjfcxktu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:phone-arrow-down-left-20-solid" /></template>
