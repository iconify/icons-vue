<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycg7u9b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycg7u9b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mower-bag" /></template>
