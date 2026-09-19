<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixzsp0vky.css';
import '../../css/m/mup4fgbbf.css';
import '../../css/v/vo89kwbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ixzsp0vky"/><ellipse class="mup4fgbbf"/><path class="vo89kwbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:social-myspace" /></template>
