<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuj0oo5gw.css';
import '../../css/v/vr9r2nw0d.css';
import '../../css/v/vllgg5aaa.css';
import '../../css/s/s50j-khsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuj0oo5gw"/><path class="vr9r2nw0d"/><path class="vllgg5aaa"/><path class="s50j-khsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sliders-v" /></template>
