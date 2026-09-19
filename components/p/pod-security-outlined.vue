<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxftmab1w.css';
import '../../css/n/n8m_h_bkm.css';
import '../../css/c/cum1b9uvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxftmab1w"/><circle class="n8m_h_bkm"/><path class="cum1b9uvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:pod-security-outlined" /></template>
