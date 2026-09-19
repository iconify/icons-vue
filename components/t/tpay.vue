<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pltis2bxu.css';
import '../../css/m/md286fbip.css';
import '../../css/x/xwvba7bli.css';
import '../../css/b/b88gxdbzy.css';
import '../../css/n/nffljcb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="pltis2bxu"/><g class="md286fbip"><path class="xwvba7bli"/><path class="b88gxdbzy"/><path class="nffljcb4c"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:tpay" /></template>
