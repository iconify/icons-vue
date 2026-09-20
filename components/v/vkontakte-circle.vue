<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5q1bccnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5q1bccnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vkontakte-circle" /></template>
