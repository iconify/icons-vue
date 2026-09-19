<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hosm0mb0b.css';
import '../../css/l/l1k7wx54r.css';
import '../../css/u/uz9y04thb.css';
import '../../css/s/sr2rlrpls.css';
import '../../css/s/sioms0bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hosm0mb0b"/><path class="l1k7wx54r"/><path class="uz9y04thb"/><path class="sr2rlrpls"/><path class="sioms0bto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rocket" /></template>
