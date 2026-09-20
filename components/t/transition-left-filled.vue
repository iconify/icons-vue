<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teyukk8yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teyukk8yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transition-left-filled" /></template>
