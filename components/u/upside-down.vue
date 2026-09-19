<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqbkv8u2i.css';
import '../../css/a/a-nr90z_g.css';
import '../../css/i/ikrkupm8l.css';
import '../../css/o/ockxf75_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="a-nr90z_g"/><circle class="ikrkupm8l"/><circle class="ockxf75_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:upside-down" /></template>
