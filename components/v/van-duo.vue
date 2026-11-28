<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-fh0ib4u.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ij3vyybgh.css';
import '../../css/w/w3i1zx0jw.css';
import '../../css/t/toteg6s6e.css';
import '../../css/r/rt7fb-bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-fh0ib4u secondary"/><g class="dt0cm9dhy primary"><path class="ij3vyybgh"/><path class="w3i1zx0jw"/><path class="toteg6s6e"/><path class="rt7fb-bar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:van-duo" /></template>
