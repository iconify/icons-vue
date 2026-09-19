<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3jxn1xds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u3jxn1xds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mosquito-collection" /></template>
