<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkqky1bmv.css';
import '../../css/c/cps_4vb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkqky1bmv"/><path class="cps_4vb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wallet-filled" /></template>
