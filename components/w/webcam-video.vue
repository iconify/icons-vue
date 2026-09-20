<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkb3oqbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jkb3oqbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:webcam-video" /></template>
