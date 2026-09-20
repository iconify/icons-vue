<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwpo4xbeq.css';
import '../../css/o/ofc_1ckbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lwpo4xbeq"/><path class="ofc_1ckbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rauthy" /></template>
