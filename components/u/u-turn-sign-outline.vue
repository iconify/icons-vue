<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/ifbmssbgp.css';
import '../../css/u/u4mnyvb1x.css';
import '../../css/e/ebhu59bkz.css';
import '../../css/i/i_46mcc2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ifbmssbgp"/><path class="u4mnyvb1x"/><path class="ebhu59bkz"/><path class="i_46mcc2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:u-turn-sign-outline" /></template>
