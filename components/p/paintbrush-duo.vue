<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byk3aib_c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/u39c_yipz.css';
import '../../css/t/t2sswdyyp.css';
import '../../css/x/xoiwp6hbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byk3aib_c secondary"/><g class="dt0cm9dhy primary"><path class="u39c_yipz"/><path class="t2sswdyyp"/><path class="xoiwp6hbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:paintbrush-duo" /></template>
