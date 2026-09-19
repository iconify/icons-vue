<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6u6kmbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h6u6kmbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:tooth" /></template>
