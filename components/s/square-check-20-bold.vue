<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xalnqm_-k.css';
import '../../css/p/pjtb2zjhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xalnqm_-k"/><path class="pjtb2zjhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-check-20-bold" /></template>
