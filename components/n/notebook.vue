<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb1xkjbuo.css';
import '../../css/y/yg7xgph3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mb1xkjbuo"/><path class="yg7xgph3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:notebook" /></template>
