<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yure3d40v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yure3d40v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:watch-alt" /></template>
