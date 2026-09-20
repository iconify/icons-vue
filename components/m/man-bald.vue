<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txk94-jpc.css';
import '../../css/a/amn_b-_3e.css';
import '../../css/q/qrwhk6b5f.css';
import '../../css/l/l4css97ah.css';
import '../../css/w/wkz0_n5gi.css';
import '../../css/q/q3aj0vory.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="txk94-jpc"/><path class="amn_b-_3e"/><path class="qrwhk6b5f"/><path class="l4css97ah"/><path class="wkz0_n5gi"/><path class="q3aj0vory"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:man-bald" /></template>
