<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc4mrmqdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc4mrmqdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:move-vertical" /></template>
