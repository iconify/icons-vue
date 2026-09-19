<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u48w4hbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u48w4hbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paper-clip" /></template>
