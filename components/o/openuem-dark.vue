<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggvn7iwto.css';
import '../../css/x/x5x2_1b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ggvn7iwto"/><path class="x5x2_1b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openuem-dark" /></template>
