<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuwub-f6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuwub-f6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:underline" /></template>
