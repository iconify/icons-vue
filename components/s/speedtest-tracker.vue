<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0q8t5bbo.css';
import '../../css/d/dmf_nf1iq.css';
import '../../css/f/fw-djbcff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0q8t5bbo"/><path class="dmf_nf1iq"/><path class="fw-djbcff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:speedtest-tracker" /></template>
