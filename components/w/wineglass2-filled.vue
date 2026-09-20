<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekn5macxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekn5macxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wineglass2-filled" /></template>
