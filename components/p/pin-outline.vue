<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mljob0-zg.css';
import '../../css/f/fs2axpb2l.css';
import '../../css/s/sq5vlkbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="mljob0-zg"/><path class="fs2axpb2l"/><circle class="sq5vlkbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:pin-outline" /></template>
