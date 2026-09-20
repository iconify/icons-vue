<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/numv4vb1m.css';
import '../../css/s/snpiwsb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="numv4vb1m"/><circle class="snpiwsb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:orange-circle" /></template>
