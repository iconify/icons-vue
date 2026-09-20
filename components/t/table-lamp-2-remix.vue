<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-ka_fbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="n-ka_fbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:table-lamp-2-remix" /></template>
