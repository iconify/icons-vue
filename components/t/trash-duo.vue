<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qi9j3qbbt.css';
import '../../css/x/xx2uf6brd.css';
import '../../css/f/fnqqe5b5e.css';
import '../../css/o/oavb46-pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qi9j3qbbt"/><path class="wm-a xx2uf6brd"/><path class="fnqqe5b5e"/><path class="oavb46-pc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trash-duo" /></template>
