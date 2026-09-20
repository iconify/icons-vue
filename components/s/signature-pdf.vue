<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhktnebyi.css';
import '../../css/x/x3okx1b0y.css';
import '../../css/w/wkj5pkqok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhktnebyi"/><path class="x3okx1b0y"/><path class="wkj5pkqok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:signature-pdf" /></template>
