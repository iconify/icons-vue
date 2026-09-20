<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be-q5ibtf.css';
import '../../css/o/oe3dp0-yz.css';
import '../../css/x/xsj4v2blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="be-q5ibtf"/><path class="oe3dp0-yz"/><path class="xsj4v2blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stirling-pdf" /></template>
