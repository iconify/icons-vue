<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdd_c94rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pdd_c94rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:search-visual-solid" /></template>
