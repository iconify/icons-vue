<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fs124bhwf.css';
import '../../css/m/ms8df3btg.css';
import '../../css/y/yth7llb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fs124bhwf"/><path class="ms8df3btg"/><path class="yth7llb8a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:safe-open" /></template>
