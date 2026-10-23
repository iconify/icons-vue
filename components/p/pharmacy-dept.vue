<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt6cdybgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dt6cdybgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pharmacy-dept" /></template>
