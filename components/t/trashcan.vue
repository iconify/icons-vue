<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi1r8vbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="vi1r8vbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:trashcan" /></template>
