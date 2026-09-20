<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5qa4em6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5qa4em6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:oven-mitts-filled" /></template>
