<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz0m0tbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz0m0tbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plaster" /></template>
