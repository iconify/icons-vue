<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmyuz8c8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmyuz8c8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:volume-cross-outline" /></template>
