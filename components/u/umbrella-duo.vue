<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz-qoubxo.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fz90fnpjg.css';
import '../../css/q/qoxrnac0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz-qoubxo secondary"/><g class="dt0cm9dhy primary"><path class="fz90fnpjg"/><path class="qoxrnac0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:umbrella-duo" /></template>
