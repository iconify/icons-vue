<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k66tt2kvs.css';
import '../../css/w/w5e8dbcrx.css';
import '../../css/k/k8us2bvxz.css';
import '../../css/y/yz4eus-9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k66tt2kvs"/><path class="w5e8dbcrx"/><path class="k8us2bvxz"/><circle class="yz4eus-9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medical-kit-line-duotone" /></template>
