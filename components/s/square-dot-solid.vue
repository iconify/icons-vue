<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfrdicc-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfrdicc-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-dot-solid" /></template>
