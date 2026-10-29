<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgjz2mb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgjz2mb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-top" /></template>
