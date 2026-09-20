<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjhopx1lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjhopx1lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:shimmer-evm" /></template>
