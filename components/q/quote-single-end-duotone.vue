<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmtv38vfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmtv38vfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:quote-single-end-duotone" /></template>
