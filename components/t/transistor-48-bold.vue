<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owfef_bia.css';
import '../../css/e/e8e1iqbrn.css';
import '../../css/m/m7c60mbxm.css';
import '../../css/b/bz-wdcbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="owfef_bia"/><path class="e8e1iqbrn"/><path class="m7c60mbxm"/><path class="bz-wdcbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transistor-48-bold" /></template>
