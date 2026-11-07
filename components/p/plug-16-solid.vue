<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5j52ibul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i5j52ibul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:plug-16-solid" /></template>
