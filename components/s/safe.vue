<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uakfjcbyb.css';
import '../../css/s/spxxfgbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uakfjcbyb"/><path class="spxxfgbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:safe" /></template>
