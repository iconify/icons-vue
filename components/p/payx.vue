<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycy63pt0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ycy63pt0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:payx" /></template>
