<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yximimb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="yximimb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:routeralt" /></template>
