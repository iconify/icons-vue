<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp0mn-ncp.css';
import '../../css/g/gxglj2bzq.css';
import '../../css/d/dq8fo2c6v.css';
import '../../css/e/ey9tmrrek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bp0mn-ncp"/><path class="gxglj2bzq"/><path class="dq8fo2c6v"/><path class="ey9tmrrek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:satellite-20-bold" /></template>
