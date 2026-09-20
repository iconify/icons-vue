<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igw3ambgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igw3ambgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-checkbox-ascending" /></template>
