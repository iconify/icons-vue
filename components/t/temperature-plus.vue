<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azf7pht0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azf7pht0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:temperature-plus" /></template>
