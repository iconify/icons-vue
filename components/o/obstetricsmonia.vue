<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3s-podyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x3s-podyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:obstetricsmonia" /></template>
