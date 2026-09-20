<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb7l0mbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb7l0mbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-on-fill" /></template>
