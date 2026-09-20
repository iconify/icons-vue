<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi6nv12pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi6nv12pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:step-forward" /></template>
