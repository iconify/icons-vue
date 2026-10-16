<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fag_tsbej.css';
import '../../css/i/iz5bv-bjz.css';
import '../../css/o/oc-waz6tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fag_tsbej"/><path class="iz5bv-bjz"/><path class="oc-waz6tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:safety-boot-48" /></template>
