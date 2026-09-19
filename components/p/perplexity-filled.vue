<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5172_-am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w5172_-am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:perplexity-filled" /></template>
