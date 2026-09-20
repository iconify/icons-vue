<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlggp481q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlggp481q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:roon" /></template>
