<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko_c4j18e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ko_c4j18e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:volume-off-fill" /></template>
