<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxmbj9awl.css';
import '../../css/c/cv0y2ubog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxmbj9awl"/><path class="cv0y2ubog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:python" /></template>
