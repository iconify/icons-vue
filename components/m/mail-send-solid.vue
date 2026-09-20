<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf-dlbakk.css';
import '../../css/l/l_7c63odl.css';
import '../../css/s/srjf_ccfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nf-dlbakk"/><path class="l_7c63odl"/><path clip-rule="evenodd" class="srjf_ccfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mail-send-solid" /></template>
