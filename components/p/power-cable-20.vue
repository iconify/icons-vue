<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx3ng-mzk.css';
import '../../css/y/y8c1zsvzo.css';
import '../../css/z/zc3xw3bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qx3ng-mzk"/><path class="y8c1zsvzo"/><path class="zc3xw3bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-cable-20" /></template>
