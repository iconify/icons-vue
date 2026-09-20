<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuq22r3pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuq22r3pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-horizontal" /></template>
