<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj_99kb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wj_99kb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:scale-to-original" /></template>
