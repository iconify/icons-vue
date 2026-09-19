<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-xk_ruej.css';
import '../../css/y/yiz97dbjs.css';
import '../../css/l/ldaz7_bsh.css';
import '../../css/h/h2s924byy.css';
import '../../css/g/g07dr6bbn.css';
import '../../css/n/nndxyclzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k-xk_ruej"/><path class="yiz97dbjs"/><path class="ldaz7_bsh"/><path class="h2s924byy"/><path class="g07dr6bbn"/><path class="nndxyclzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pouting" /></template>
