<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxy23kbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cxy23kbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:zap-16" /></template>
