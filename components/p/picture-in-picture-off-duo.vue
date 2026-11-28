<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djy0icb9y.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/clyp0ebhu.css';
import '../../css/b/bqp-165ha.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djy0icb9y secondary"/><g class="dt0cm9dhy primary"><path class="clyp0ebhu"/><path class="bqp-165ha"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:picture-in-picture-off-duo" /></template>
