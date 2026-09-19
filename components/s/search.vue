<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl7z8j7sc.css';
import '../../css/f/fg6p2fbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="zl7z8j7sc"/><path class="fg6p2fbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:search" /></template>
