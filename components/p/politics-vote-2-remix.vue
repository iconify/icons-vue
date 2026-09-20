<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw8oyvbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hw8oyvbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:politics-vote-2-remix" /></template>
