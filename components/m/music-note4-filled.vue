<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4of0kbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4of0kbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music-note4-filled" /></template>
