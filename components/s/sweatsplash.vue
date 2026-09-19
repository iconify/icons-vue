<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdgikwjle.css';
import '../../css/c/certo-bxv.css';
import '../../css/j/j8y488bff.css';
import '../../css/w/w9-2og5ix.css';
import '../../css/x/xydsivb4a.css';
import '../../css/h/h2r_jvb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qdgikwjle"/><path class="certo-bxv"/><path class="j8y488bff"/><path class="w9-2og5ix"/><path class="xydsivb4a"/><path class="h2r_jvb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:sweatsplash" /></template>
