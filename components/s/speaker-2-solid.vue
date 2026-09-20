<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvydekbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tvydekbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:speaker-2-solid" /></template>
