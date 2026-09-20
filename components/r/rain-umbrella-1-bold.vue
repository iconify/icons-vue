<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qypshgbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qypshgbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:rain-umbrella-1-bold" /></template>
