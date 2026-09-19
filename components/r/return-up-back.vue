<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzp_awbau.css';
import '../../css/n/nar_pyley.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzp_awbau"/><path class="nar_pyley"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:return-up-back" /></template>
