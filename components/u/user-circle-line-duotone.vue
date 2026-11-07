<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n9a_lybsm.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/c/c_k_34b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="n9a_lybsm"/><circle class="shu3xdl9q"/><path class="c_k_34b-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-circle-line-duotone" /></template>
