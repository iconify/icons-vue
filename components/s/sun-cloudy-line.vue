<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3sal8b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3sal8b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-cloudy-line" /></template>
