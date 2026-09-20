<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jndmtptdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jndmtptdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pea-filled" /></template>
