<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjp6-toga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pjp6-toga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:star-2-remix" /></template>
