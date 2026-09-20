<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv2_s9bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv2_s9bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-vacuum-cleaner-outline" /></template>
