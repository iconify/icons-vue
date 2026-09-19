<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/s/s-us9ombj.css';
import '../../css/a/a188s0iwo.css';
import '../../css/m/m40g5_blz.css';
import '../../css/x/xa2l19otp.css';
import '../../css/i/i8hr72bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="s-us9ombj"/><path class="a188s0iwo"/><path class="m40g5_blz"/><path class="xa2l19otp"/><path class="i8hr72bcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:mask" /></template>
