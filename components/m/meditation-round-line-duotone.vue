<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v6pzvpfzc.css';
import '../../css/i/i7h4d0b1t.css';
import '../../css/n/n2fu-sj-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v6pzvpfzc"/><path class="i7h4d0b1t"/><path class="n2fu-sj-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:meditation-round-line-duotone" /></template>
