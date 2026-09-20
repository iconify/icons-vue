<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0ibpobqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0ibpobqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:th-large" /></template>
