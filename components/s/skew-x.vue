<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/humv9earr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="humv9earr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:skew-x" /></template>
