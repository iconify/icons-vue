<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh-18tbsw.css';
import '../../css/f/ftv6d47py.css';
import '../../css/l/l-ba9qber.css';
import '../../css/d/dertp7bua.css';
import '../../css/r/r-r5xdlfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="jh-18tbsw"/><path class="ftv6d47py"/><circle class="l-ba9qber"/><circle class="dertp7bua"/><path class="r-r5xdlfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:network-4-reference" /></template>
