<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brqimlb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brqimlb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stopwatch-music" /></template>
