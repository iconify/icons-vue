<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am_i4l4_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am_i4l4_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:share" /></template>
