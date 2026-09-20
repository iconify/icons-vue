<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbeyeibrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbeyeibrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:task-square-filled" /></template>
