<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u035nnboi.css';
import '../../css/o/oj8vp5bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u035nnboi"/><path class="oj8vp5bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:velero" /></template>
