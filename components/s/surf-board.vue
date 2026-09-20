<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbpzzzu3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zbpzzzu3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:surf-board" /></template>
