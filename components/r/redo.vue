<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca9tmgz0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca9tmgz0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:redo" /></template>
