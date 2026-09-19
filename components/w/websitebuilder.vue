<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyfts6bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wyfts6bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:websitebuilder" /></template>
