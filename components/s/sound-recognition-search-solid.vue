<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bykfut8oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bykfut8oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:sound-recognition-search-solid" /></template>
