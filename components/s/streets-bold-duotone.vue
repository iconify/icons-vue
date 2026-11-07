<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfp_v5kne.css';
import '../../css/o/ow6-kpbfs.css';
import '../../css/q/qcydym7-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfp_v5kne"/><path class="ow6-kpbfs"/><path class="qcydym7-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-bold-duotone" /></template>
