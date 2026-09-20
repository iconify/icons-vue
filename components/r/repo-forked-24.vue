<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdm9jbcnr.css';
import '../../css/e/erp-9sbvf.css';
import '../../css/m/mztshossz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdm9jbcnr"/><path class="erp-9sbvf"/><path class="mztshossz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-forked-24" /></template>
