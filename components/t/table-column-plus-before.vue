<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isrc4zxns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isrc4zxns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-column-plus-before" /></template>
