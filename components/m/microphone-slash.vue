<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qthr_h6oz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qthr_h6oz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:microphone-slash" /></template>
