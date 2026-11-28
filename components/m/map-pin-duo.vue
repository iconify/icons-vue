<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0r16e4cs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/axayjezpl.css';
import '../../css/h/h-xz0jv-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0r16e4cs secondary"/><g class="dt0cm9dhy primary"><path class="axayjezpl"/><circle class="h-xz0jv-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-duo" /></template>
