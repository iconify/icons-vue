<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4qdjcpug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4qdjcpug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wave-pulse-filled" /></template>
