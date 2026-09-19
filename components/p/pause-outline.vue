<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myw4k0vkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pause-outline"><path class="Vector myw4k0vkw" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:pause-outline" /></template>
