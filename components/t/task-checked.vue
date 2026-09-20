<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_h6_bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_h6_bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:task-checked" /></template>
