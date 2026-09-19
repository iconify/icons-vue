<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovzl77bwj.css';
import '../../css/m/mf1r0nbce.css';
import '../../css/w/wz-tl9bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ovzl77bwj"/><path class="mf1r0nbce"/><path class="wz-tl9bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:qwik" /></template>
