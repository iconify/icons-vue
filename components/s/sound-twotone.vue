<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aij89zban.css';
import '../../css/q/qumb2w6hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="aij89zban"/><path class="qumb2w6hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sound-twotone" /></template>
