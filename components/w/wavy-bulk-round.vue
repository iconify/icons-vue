<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umqey9sxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umqey9sxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-bulk-round" /></template>
