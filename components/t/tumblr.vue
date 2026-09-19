<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xggs1mbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xggs1mbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:tumblr" /></template>
