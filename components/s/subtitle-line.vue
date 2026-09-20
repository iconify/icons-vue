<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1o33v6nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1o33v6nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:subtitle-line" /></template>
