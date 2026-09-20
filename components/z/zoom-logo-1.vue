<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiauddejf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiauddejf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:zoom-logo-1" /></template>
