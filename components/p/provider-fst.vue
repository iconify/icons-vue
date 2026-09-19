<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmsw3db2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nmsw3db2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:provider-fst" /></template>
