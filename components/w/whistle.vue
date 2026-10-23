<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtgg2kbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtgg2kbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:whistle" /></template>
