<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4x3c_beq.css';
import '../../css/k/k8ixw89dy.css';
import '../../css/c/cbp_2nbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n4x3c_beq"/><path class="k8ixw89dy"/><circle class="cbp_2nbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-pages-rtl" /></template>
