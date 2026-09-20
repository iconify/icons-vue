<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfvn_dgph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wfvn_dgph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:volume-up-ltr" /></template>
