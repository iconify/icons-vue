<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buzb721ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buzb721ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-3d" /></template>
