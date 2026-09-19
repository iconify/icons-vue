<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hps_kcbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hps_kcbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:pied-piper-pp" /></template>
