<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7n94zb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7n94zb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:oval" /></template>
