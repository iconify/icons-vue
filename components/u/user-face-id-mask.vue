<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvjckikhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nvjckikhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:user-face-id-mask" /></template>
