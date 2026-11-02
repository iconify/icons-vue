<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4t1_jbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4t1_jbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:question-line" /></template>
