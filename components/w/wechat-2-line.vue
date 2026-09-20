<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw-tn0_ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw-tn0_ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wechat-2-line" /></template>
