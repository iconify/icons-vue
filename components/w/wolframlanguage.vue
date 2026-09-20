<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m38zlzbtp.css';
import '../../css/i/iv4nqz7tn.css';
import '../../css/f/f6g8zlbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g transform="translate(-.009 -.001)scale(.12121)"><circle class="m38zlzbtp"/><path class="iv4nqz7tn"/><path class="f6g8zlbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:wolframlanguage" /></template>
