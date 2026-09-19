<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nabblub0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nabblub0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:thunderbolt" /></template>
