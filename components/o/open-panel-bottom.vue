<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nft3n5nlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nft3n5nlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:open-panel-bottom" /></template>
