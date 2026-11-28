<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lidd10bek.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s-3b3ce9i.css';
import '../../css/i/iy-_h6bqy.css';
import '../../css/f/fh4sb3bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lidd10bek secondary"/><g class="dt0cm9dhy primary"><path class="s-3b3ce9i"/><path class="iy-_h6bqy"/><path class="fh4sb3bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stool-duo" /></template>
