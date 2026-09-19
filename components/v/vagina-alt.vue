<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uord8ebkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uord8ebkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vagina-alt" /></template>
