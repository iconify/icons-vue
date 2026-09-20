<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwl_c-0if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mwl_c-0if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pool-ladder-remix" /></template>
