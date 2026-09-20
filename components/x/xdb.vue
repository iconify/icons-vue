<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrcz8lelj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrcz8lelj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xdb" /></template>
