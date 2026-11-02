<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b26kvl1wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b26kvl1wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:robot-line" /></template>
