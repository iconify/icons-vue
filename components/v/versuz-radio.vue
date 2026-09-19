<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9bfyrst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv9bfyrst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:versuz-radio" /></template>
