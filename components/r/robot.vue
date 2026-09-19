<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx6o3lh-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hx6o3lh-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:robot" /></template>
