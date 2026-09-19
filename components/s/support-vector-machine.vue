<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0oxfv-jn.css';
import '../../css/y/yf-k82b-b.css';
import '../../css/k/krcvqcb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="o0oxfv-jn"/><circle class="yf-k82b-b"/><path class="krcvqcb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:support-vector-machine" /></template>
