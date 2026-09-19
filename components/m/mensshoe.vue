<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ya_cbut.css';
import '../../css/d/ds4k--4aj.css';
import '../../css/f/fqt_spbrj.css';
import '../../css/h/h6sr52b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="f_ya_cbut"/><path class="ds4k--4aj"/><path class="fqt_spbrj"/><path class="h6sr52b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:mensshoe" /></template>
