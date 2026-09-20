<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txfwdmb_e.css';
import '../../css/s/slra1_f-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txfwdmb_e"/><path clip-rule="evenodd" class="slra1_f-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:payoneer" /></template>
