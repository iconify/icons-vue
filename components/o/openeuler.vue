<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmeey5brg.css';
import '../../css/q/q194_cbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lmeey5brg"/><path class="q194_cbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openeuler" /></template>
