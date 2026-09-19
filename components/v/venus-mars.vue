<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm2tfmrxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qm2tfmrxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:venus-mars" /></template>
