<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa8cast3m.css';
import '../../css/q/qxzfcfqis.css';
import '../../css/p/p10chkbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oa8cast3m"/><path class="qxzfcfqis"/><path class="p10chkbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:medal-20" /></template>
