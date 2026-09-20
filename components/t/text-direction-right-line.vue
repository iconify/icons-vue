<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7lpn1bfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7lpn1bfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-direction-right-line" /></template>
