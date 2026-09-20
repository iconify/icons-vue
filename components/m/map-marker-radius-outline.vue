<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orkur467v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orkur467v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-marker-radius-outline" /></template>
