<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv57_8jja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yv57_8jja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shield-alert" /></template>
