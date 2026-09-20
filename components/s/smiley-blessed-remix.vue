<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd8c9vixx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hd8c9vixx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:smiley-blessed-remix" /></template>
