<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo5lmccvl.css';
import '../../css/p/p54bnaccc.css';
import '../../css/p/px847tbvl.css';
import '../../css/t/txado3aqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uo5lmccvl"/><path class="p54bnaccc"/><path class="px847tbvl"/><path class="txado3aqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:postgresql" /></template>
