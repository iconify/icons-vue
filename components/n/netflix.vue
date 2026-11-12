<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8s2800fo.css';
import '../../css/m/ma-2opx8e.css';
import '../../css/u/uruqrcc2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n8s2800fo"/><path class="ma-2opx8e"/><path class="uruqrcc2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netflix" /></template>
