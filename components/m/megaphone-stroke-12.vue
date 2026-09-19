<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3-abubmf.css';
import '../../css/j/j9m0dh2uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y3-abubmf"/><path class="j9m0dh2uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:megaphone-stroke-12" /></template>
