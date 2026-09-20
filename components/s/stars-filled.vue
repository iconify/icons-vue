<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiwx514tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiwx514tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:stars-filled" /></template>
