<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0tnlimht.css';
import '../../css/x/xc9imsb1x.css';
import '../../css/f/f_84nivhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s0tnlimht"/><path class="xc9imsb1x"/><path class="f_84nivhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:zil" /></template>
