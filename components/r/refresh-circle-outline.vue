<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1h_8isxf.css';
import '../../css/e/eu7dfbmgb.css';
import '../../css/q/q-tflgzje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b1h_8isxf"/><path class="eu7dfbmgb"/><path class="q-tflgzje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:refresh-circle-outline" /></template>
