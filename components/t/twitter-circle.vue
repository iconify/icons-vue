<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_64wx3zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_64wx3zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:twitter-circle" /></template>
