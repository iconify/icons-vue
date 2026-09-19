<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg8880iad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rg8880iad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:unlock-filled" /></template>
