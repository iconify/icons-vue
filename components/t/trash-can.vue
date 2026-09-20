<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srd7lnbfg.css';
import '../../css/w/waqnvi5sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="srd7lnbfg"/><path class="waqnvi5sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:trash-can" /></template>
