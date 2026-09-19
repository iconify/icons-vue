<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3fg7597e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3fg7597e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:moving-desk" /></template>
