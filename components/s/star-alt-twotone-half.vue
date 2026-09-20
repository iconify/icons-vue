<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5ukuz.css';
import '../../css/w/wtwpul.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-66.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ukuz"/><path class="wtwpul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-alt-twotone-half" /></template>
