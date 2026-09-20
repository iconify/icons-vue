<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjzkr_tlv.css';
import '../../css/w/wdhb6ixpv.css';
import '../../css/a/axh1avblo.css';
import '../../css/o/odrl5kb4x.css';
import '../../css/k/ky8obwb_s.css';
import '../../css/o/o9baeq6dr.css';
import '../../css/n/n3lkwqp-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tjzkr_tlv"/><path class="wdhb6ixpv"/><path class="axh1avblo"/><path class="odrl5kb4x"/><path class="ky8obwb_s"/><path class="o9baeq6dr"/><path class="n3lkwqp-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pushpin" /></template>
