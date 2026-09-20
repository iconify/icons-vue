<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elb82nbbj.css';
import '../../css/a/aewymtpsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="elb82nbbj"/><path class="aewymtpsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:power-sleep-symbol" /></template>
