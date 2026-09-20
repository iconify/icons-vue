<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csypp5bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="csypp5bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:tree-1-solid" /></template>
