<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/f/f6q6bbc7u.css';
import '../../css/y/ylp_vncrn.css';
import '../../css/g/gya453bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="f6q6bbc7u"/><path class="ylp_vncrn"/><path class="gya453bci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:movie" /></template>
