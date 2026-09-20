<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zctq2zbbr.css';
import '../../css/z/zoj-nnnyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zctq2zbbr"/><path class="zoj-nnnyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mntl" /></template>
