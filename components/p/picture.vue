<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvhljtbdd.css';
import '../../css/d/dwu99p9fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nvhljtbdd"/><path class="dwu99p9fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:picture" /></template>
