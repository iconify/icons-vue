<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvyne8bgw.css';
import '../../css/z/zeqclcbxs.css';
import '../../css/i/ipw49hbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qvyne8bgw"/><path class="zeqclcbxs"/><path class="ipw49hbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:taskade-wordmark" /></template>
