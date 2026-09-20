<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfsq0xb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfsq0xb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-none-outline" /></template>
