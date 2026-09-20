<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra_8wxb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_8wxb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:mask-light" /></template>
