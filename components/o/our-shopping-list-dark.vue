<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n67a_j-wg.css';
import '../../css/q/qjx3e9jap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="n67a_j-wg"/><path class="qjx3e9jap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:our-shopping-list-dark" /></template>
