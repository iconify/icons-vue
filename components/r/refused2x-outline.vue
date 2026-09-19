<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpwhqqa6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mpwhqqa6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:refused2x-outline" /></template>
