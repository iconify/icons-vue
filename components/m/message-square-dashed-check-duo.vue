<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjd2x0bfl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jrgpz7bvh.css';
import '../../css/g/gcbea1zjt.css';
import '../../css/j/j7k7ottks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjd2x0bfl secondary"/><g class="dt0cm9dhy primary"><path class="jrgpz7bvh"/><path class="gcbea1zjt"/><path class="j7k7ottks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-dashed-check-duo" /></template>
