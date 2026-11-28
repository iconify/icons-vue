<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy9sl0d-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy9sl0d-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-heart" /></template>
