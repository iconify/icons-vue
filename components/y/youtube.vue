<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b16bxbgpf.css';
import '../../css/y/yyxdkxbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":180};
const content = `<path class="b16bxbgpf"/><path class="yyxdkxbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:youtube" /></template>
