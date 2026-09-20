<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6fnyrbeo.css';
import '../../css/p/pd0f2kbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6fnyrbeo"/><path class="pd0f2kbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-petrified" /></template>
