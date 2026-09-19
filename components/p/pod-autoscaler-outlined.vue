<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftiuf-5wm.css';
import '../../css/h/h2k8cfbxb.css';
import '../../css/h/hh18pwssq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftiuf-5wm"/><circle class="h2k8cfbxb"/><path class="hh18pwssq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:pod-autoscaler-outlined" /></template>
