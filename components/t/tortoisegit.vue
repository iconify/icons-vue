<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz0kxdb2u.css';
import '../../css/b/b5q998adc.css';
import '../../css/i/ieesa9btj.css';
import '../../css/y/yefg016-l.css';
import '../../css/t/tpuc-hf5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sz0kxdb2u"/><path class="b5q998adc"/><path class="ieesa9btj"/><path class="yefg016-l"/><path class="tpuc-hf5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tortoisegit" /></template>
