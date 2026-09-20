<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyu-pdxjs.css';
import '../../css/v/v-coqgbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="qyu-pdxjs"/><path class="v-coqgbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextpvr" /></template>
