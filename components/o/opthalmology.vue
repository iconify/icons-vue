<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2wg8dbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i2wg8dbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:opthalmology" /></template>
