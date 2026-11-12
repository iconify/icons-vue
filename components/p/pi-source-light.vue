<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9w5brbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k9w5brbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pi-source-light" /></template>
