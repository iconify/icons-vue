<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz7vnzbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7vnzbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:stopwatch" /></template>
