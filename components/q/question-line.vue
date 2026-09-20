<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvxexubbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvxexubbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:question-line" /></template>
