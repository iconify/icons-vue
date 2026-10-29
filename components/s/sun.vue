<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4bp63bqf.css';
import '../../css/u/upne6j1lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a x4bp63bqf"/><path class="upne6j1lj wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sun" /></template>
