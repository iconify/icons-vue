<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixh097b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ixh097b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shield-check-20-solid" /></template>
