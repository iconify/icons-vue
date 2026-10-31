<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_3kegdhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_3kegdhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:strikethrough-duotone-round" /></template>
