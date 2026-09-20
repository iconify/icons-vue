<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zir0f_raf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zir0f_raf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:school-15" /></template>
