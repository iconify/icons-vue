<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq9u21biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kq9u21biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:user" /></template>
