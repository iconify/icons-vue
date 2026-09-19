<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6hkc5b2j.css';
import '../../css/o/op2gjqblh.css';
import '../../css/x/xmd1k6ysb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g6hkc5b2j"/><path class="op2gjqblh"/><path class="xmd1k6ysb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:raspberrypi" /></template>
