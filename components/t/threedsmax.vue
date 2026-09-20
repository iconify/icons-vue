<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc7tfnbgj.css';
import '../../css/e/eu3o_ilxw.css';
import '../../css/b/b1ql3zb2y.css';
import '../../css/g/g6vgndbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tc7tfnbgj"/><path class="eu3o_ilxw"/><path class="b1ql3zb2y"/><path class="g6vgndbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:threedsmax" /></template>
