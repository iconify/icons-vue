<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjph9dmcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjph9dmcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:northeast-southwest-line" /></template>
