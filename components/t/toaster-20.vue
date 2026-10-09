<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxo9vzbcf.css';
import '../../css/c/ckf78acjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cxo9vzbcf"/><path class="ckf78acjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toaster-20" /></template>
