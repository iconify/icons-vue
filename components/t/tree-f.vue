<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrfh4s3tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-1.5};
const content = `<path class="zrfh4s3tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tree-f" /></template>
