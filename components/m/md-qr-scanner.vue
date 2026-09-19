<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ammsdacwb.css';
import '../../css/e/e4mjywbbo.css';
import '../../css/t/tnw_cksns.css';
import '../../css/d/dyglo7bbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ammsdacwb"/><path class="e4mjywbbo"/><path class="tnw_cksns"/><path class="dyglo7bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-qr-scanner" /></template>
