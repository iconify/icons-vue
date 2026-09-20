<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxfhyr3rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxfhyr3rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:plane-takeoff" /></template>
