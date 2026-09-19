<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxjt1bbjd.css';
import '../../css/k/k_ivpjbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxjt1bbjd"/><path class="k_ivpjbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pie-chart-alt-filled" /></template>
