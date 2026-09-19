<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc6m4nbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc6m4nbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zwift" /></template>
