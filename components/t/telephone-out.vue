<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl145g8bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl145g8bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone-out" /></template>
