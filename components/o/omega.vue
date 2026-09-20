<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd-j90bhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd-j90bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:omega" /></template>
