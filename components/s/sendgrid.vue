<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p30wh0w8d.css';
import '../../css/q/qf-jq2kcn.css';
import '../../css/a/awltb5o6o.css';
import '../../css/m/m5ig3__2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p30wh0w8d"/><path class="qf-jq2kcn"/><path class="awltb5o6o"/><path class="m5ig3__2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sendgrid" /></template>
