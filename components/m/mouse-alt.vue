<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxp6wwb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxp6wwb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:mouse-alt" /></template>
