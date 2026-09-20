<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko0725l_d.css';
import '../../css/f/fbeaqo8bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko0725l_d"/><path clip-rule="evenodd" class="fbeaqo8bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search-split-solid" /></template>
