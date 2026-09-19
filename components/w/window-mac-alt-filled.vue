<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j90bwrx1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j90bwrx1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:window-mac-alt-filled" /></template>
