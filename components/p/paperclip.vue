<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy1dny6wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="cy1dny6wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:paperclip" /></template>
