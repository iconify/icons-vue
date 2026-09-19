<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fedk4wb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fedk4wb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:waist-circumference-outline" /></template>
