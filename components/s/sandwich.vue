<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fr5386brj.css';
import '../../css/c/cxlsd5blc.css';
import '../../css/z/zypf8t5ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fr5386brj"/><path class="cxlsd5blc"/><rect class="zypf8t5ce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sandwich" /></template>
