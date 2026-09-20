<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwu_i49mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nwu_i49mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:return-3-solid" /></template>
