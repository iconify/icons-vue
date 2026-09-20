<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7mu6fb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7mu6fb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:threads" /></template>
