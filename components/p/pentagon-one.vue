<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgh0_tp3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hgh0_tp3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:pentagon-one" /></template>
