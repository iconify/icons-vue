<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv5n6wbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iv5n6wbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:snowflake-16-solid" /></template>
