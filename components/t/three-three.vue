<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdv_lbcih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kdv_lbcih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:three-three" /></template>
