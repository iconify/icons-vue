<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxng5pzer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gxng5pzer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-laughing-3-remix" /></template>
