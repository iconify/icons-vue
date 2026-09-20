<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxfgd9bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oxfgd9bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:music-tone-alt" /></template>
