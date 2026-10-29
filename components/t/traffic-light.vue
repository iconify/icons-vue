<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/h/hkh54t9yf.css';
import '../../css/c/cf2fsfsjn.css';
import '../../css/b/b74qgjb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="hkh54t9yf"/><path class="cf2fsfsjn"/><path class="b74qgjb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:traffic-light" /></template>
