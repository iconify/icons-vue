<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2n25kb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2n25kb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-heart-filled" /></template>
