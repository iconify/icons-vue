<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdo2oulen.css';
import '../../css/n/nfkakzbeb.css';
import '../../css/q/qd5b0vbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hdo2oulen"/><path class="nfkakzbeb"/><path class="qd5b0vbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:rules" /></template>
