<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2li7-bjp.css';
import '../../css/i/iohbeo7da.css';
import '../../css/h/hqzh9-bno.css';
import '../../css/r/rgy-3x2rx.css';
import '../../css/x/xd1ptjzsj.css';
import '../../css/m/myjxigb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2li7-bjp"/><path class="iohbeo7da"/><path class="hqzh9-bno"/><path class="rgy-3x2rx"/><path class="xd1ptjzsj"/><path class="myjxigb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pig" /></template>
