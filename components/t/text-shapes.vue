<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgbb3bemw.css';
import '../../css/u/uykx6e1uw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fgbb3bemw"/><path class="uykx6e1uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:text-shapes" /></template>
