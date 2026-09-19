<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7-6b3kbh.css';
import '../../css/x/xnaxp_oyy.css';
import '../../css/m/mj3jpacnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f7-6b3kbh"/><path class="xnaxp_oyy"/><path class="mj3jpacnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:model-s" /></template>
