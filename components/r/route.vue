<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h__8rnb5v.css';
import '../../css/x/xjh3njbok.css';
import '../../css/o/og_9js9al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h__8rnb5v"/><circle class="xjh3njbok"/><circle class="og_9js9al"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:route" /></template>
