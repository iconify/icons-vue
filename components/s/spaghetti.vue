<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yubgi-0bi.css';
import '../../css/e/e_ce5r8oh.css';
import '../../css/e/ehhfdwnok.css';
import '../../css/i/i3j_-xb4h.css';
import '../../css/b/bd20qcbyz.css';
import '../../css/m/mzve6i0yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yubgi-0bi"/><path class="e_ce5r8oh"/><path class="ehhfdwnok"/><path class="i3j_-xb4h"/><path class="bd20qcbyz"/><path class="mzve6i0yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:spaghetti" /></template>
