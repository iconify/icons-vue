<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh_gcb3dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fh_gcb3dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wechat-fill-16" /></template>
