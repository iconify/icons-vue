<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcqu-00yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dcqu-00yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:male-condom" /></template>
