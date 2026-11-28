<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc7yqrbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc7yqrbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pause-solid" /></template>
