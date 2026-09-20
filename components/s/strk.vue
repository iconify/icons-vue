<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf92wgbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf92wgbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:strk" /></template>
