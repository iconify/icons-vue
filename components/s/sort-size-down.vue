<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwh2ifarf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwh2ifarf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:sort-size-down" /></template>
