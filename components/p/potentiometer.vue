<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy6pb5_so.css';
import '../../css/v/v_5-d_bsv.css';
import '../../css/u/uquyg4b5c.css';
import '../../css/f/f93lk7bsb.css';
import '../../css/j/j2id3cc1o.css';
import '../../css/p/p92kehbzj.css';
import '../../css/w/wjjuu-hhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qy6pb5_so"/><circle class="v_5-d_bsv"/><path class="uquyg4b5c"/><path class="f93lk7bsb"/><circle class="j2id3cc1o"/><circle class="p92kehbzj"/><path class="wjjuu-hhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:potentiometer" /></template>
