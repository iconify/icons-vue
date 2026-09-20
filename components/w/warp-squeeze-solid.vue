<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl2fbrcrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jl2fbrcrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:warp-squeeze-solid" /></template>
