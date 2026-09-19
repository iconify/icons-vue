<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw_kycnzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sw_kycnzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:square-small" /></template>
