<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvnkgjbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xvnkgjbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:stop-o" /></template>
