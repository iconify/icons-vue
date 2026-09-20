<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uep79_o_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uep79_o_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:scissors-flat" /></template>
