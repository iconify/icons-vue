<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnm3l5bqe.css';
import '../../css/e/ehym_vpmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lnm3l5bqe"/><path class="ehym_vpmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wheelchair-48" /></template>
