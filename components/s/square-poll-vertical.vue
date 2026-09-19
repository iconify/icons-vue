<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxyqtbbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sxyqtbbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:square-poll-vertical" /></template>
