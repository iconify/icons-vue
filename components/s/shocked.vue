<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayrvy6blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayrvy6blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:shocked" /></template>
