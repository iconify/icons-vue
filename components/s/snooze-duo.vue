<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3c_1v0qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y3c_1v0qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:snooze-duo" /></template>
