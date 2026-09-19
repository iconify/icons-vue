<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcup4z39m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mcup4z39m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:z" /></template>
