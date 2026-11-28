<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m60pqtldl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/m-fhnx1pb.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m60pqtldl secondary"/><g class="dt0cm9dhy primary"><path class="m-fhnx1pb"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:puzzle-off-duo" /></template>
