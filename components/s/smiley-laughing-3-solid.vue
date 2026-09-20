<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-w7k98js.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-w7k98js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-laughing-3-solid" /></template>
