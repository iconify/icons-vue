<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sk8b5jbko.css';
import '../../css/i/ir80l-8id.css';
import '../../css/t/t49aahmwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sk8b5jbko"/><path class="ir80l-8id"/><path class="t49aahmwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:ringed-planet" /></template>
