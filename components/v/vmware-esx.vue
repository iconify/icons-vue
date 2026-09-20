<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgzsz4bdl.css';
import '../../css/l/l65istbut.css';
import '../../css/f/fufcd88mx.css';
import '../../css/y/y_20o_7ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fgzsz4bdl"/><path class="l65istbut"/><path class="fufcd88mx"/><path class="y_20o_7ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vmware-esx" /></template>
