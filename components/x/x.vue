<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsuub8p2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsuub8p2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:x" /></template>
