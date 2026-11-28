<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr1865n3b.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mie31z6an.css';
import '../../css/o/o-vq384-b.css';
import '../../css/f/f7x0orx7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wr1865n3b"/><g class="dt0cm9dhy primary"><path class="mie31z6an"/><circle class="o-vq384-b"/><path class="f7x0orx7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-square-duo" /></template>
