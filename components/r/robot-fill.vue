<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4q0anbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4q0anbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:robot-fill" /></template>
