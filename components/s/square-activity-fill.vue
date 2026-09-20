<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd5122bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd5122bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-activity-fill" /></template>
