<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qec1zubfq.css';
import '../../css/v/vb0zy4bpj.css';
import '../../css/s/sflimwqwt.css';
import '../../css/f/f-f29in2d.css';
import '../../css/i/is756bbga.css';
import '../../css/l/lnwims27h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qec1zubfq"/><path class="vb0zy4bpj"/><path class="sflimwqwt"/><path class="f-f29in2d"/><path class="is756bbga"/><circle class="lnwims27h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:up-button" /></template>
