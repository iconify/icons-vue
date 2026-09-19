<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w00s2nbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="w00s2nbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:user-astronaut" /></template>
