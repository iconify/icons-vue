<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwq1znuml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zwq1znuml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:railway-track-crossing-railway-track" /></template>
