<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/aiu2dac3q.css';
import '../../css/k/kpcjxbbzl.css';
import '../../css/n/ncb20ka2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aiu2dac3q"/><path class="kpcjxbbzl"/><path class="ncb20ka2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-broken" /></template>
