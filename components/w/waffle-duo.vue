<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9ny4bbtp.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nwv1ikbat.css';
import '../../css/l/ll03xspng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9ny4bbtp secondary"/><g class="dt0cm9dhy primary"><path class="nwv1ikbat"/><path class="ll03xspng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:waffle-duo" /></template>
