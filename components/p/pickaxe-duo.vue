<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb5kviydn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vj3ytwxdm.css';
import '../../css/o/op0-e7whw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb5kviydn secondary"/><g class="dt0cm9dhy primary"><path class="vj3ytwxdm"/><path class="op0-e7whw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pickaxe-duo" /></template>
