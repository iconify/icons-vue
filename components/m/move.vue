<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf_p8zb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf_p8zb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:move" /></template>
