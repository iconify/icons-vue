<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf-9gnbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xf-9gnbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:transgender" /></template>
