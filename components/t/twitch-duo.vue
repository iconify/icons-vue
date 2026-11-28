<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fukmeobbs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sdadatb0l.css';
import '../../css/d/d7nqjgwls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fukmeobbs secondary"/><g class="dt0cm9dhy primary"><path class="sdadatb0l"/><path class="d7nqjgwls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:twitch-duo" /></template>
