<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3ksii2ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r3ksii2ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:paperclip" /></template>
