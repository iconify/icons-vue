<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rprrz39yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rprrz39yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:wand-magic-sparkles-outline" /></template>
