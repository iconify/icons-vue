<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1hdf1bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="e1hdf1bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:party-popper" /></template>
