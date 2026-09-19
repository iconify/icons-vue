<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhets1rsz.css';
import '../../css/z/zl5kt1bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhets1rsz"/><path class="zl5kt1bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:voice-over-record" /></template>
