<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqz67i20m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="zqz67i20m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tablet-f" /></template>
