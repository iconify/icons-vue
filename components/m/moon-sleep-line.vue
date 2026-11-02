<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9sfw7l0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9sfw7l0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moon-sleep-line" /></template>
