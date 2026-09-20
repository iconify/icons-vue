<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-q532b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s-q532b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:tencent-weiboing-logo-solid" /></template>
