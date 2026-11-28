<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyxkz4bho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyxkz4bho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:signpost-solid" /></template>
