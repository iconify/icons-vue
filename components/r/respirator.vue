<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvh5j5b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xvh5j5b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:respirator" /></template>
