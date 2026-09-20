<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm7jb4b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm7jb4b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pause" /></template>
