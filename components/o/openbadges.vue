<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyhs6fcbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhs6fcbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:openbadges" /></template>
