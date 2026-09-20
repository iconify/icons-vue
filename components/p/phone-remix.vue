<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx2gc1csh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qx2gc1csh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:phone-remix" /></template>
