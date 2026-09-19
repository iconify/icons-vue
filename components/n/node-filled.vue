<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvxc-vbfr.css';
import '../../css/n/nq2wfabsf.css';
import '../../css/i/ishbz4cce.css';
import '../../css/s/sololpbna.css';
import '../../css/r/rt617yb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvxc-vbfr"/><circle class="nq2wfabsf"/><circle class="ishbz4cce"/><circle class="sololpbna"/><circle class="rt617yb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:node-filled" /></template>
