<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-vu5ccny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-vu5ccny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget6-filled" /></template>
