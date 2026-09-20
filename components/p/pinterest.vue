<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua2we0bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ua2we0bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pinterest" /></template>
