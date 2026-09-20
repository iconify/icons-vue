<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4t75tbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4t75tbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tornado-2-line" /></template>
