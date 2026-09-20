<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8xg3v5yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8xg3v5yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wind2-filled" /></template>
