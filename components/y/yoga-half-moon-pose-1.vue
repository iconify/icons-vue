<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x35ffibve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x35ffibve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:yoga-half-moon-pose-1" /></template>
