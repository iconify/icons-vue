<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt3xbuark.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt3xbuark"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-6" /></template>
