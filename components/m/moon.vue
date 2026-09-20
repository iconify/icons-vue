<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nms3h9f_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="nms3h9f_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:moon" /></template>
