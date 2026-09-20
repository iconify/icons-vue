<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsc74_zyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsc74_zyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:play-circle-stroke-filled" /></template>
