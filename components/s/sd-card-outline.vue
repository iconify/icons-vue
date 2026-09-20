<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4nltkd0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u4nltkd0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sd-card-outline" /></template>
