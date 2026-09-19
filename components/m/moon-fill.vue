<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjapq3bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjapq3bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:moon-fill" /></template>
