<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybqkib0xe.css';
import '../../css/t/t9chy47bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybqkib0xe"/><path class="t9chy47bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:upload-alt" /></template>
