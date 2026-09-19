<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0nxbeb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h0nxbeb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:orthopaedics" /></template>
