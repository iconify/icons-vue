<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6duhzbtn.css';
import '../../css/t/tmcnx0bgf.css';
import '../../css/j/jmp2ofbsg.css';
import '../../css/b/by48vwbxo.css';
import '../../css/m/mzqhsqb9l.css';
import '../../css/n/n5-7uibog.css';
import '../../css/c/cco9hubfk.css';
import '../../css/g/gpbcp1elw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6duhzbtn"/><path class="tmcnx0bgf"/><path class="jmp2ofbsg"/><path class="by48vwbxo"/><path class="mzqhsqb9l"/><circle class="n5-7uibog"/><circle class="cco9hubfk"/><path class="gpbcp1elw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:school" /></template>
