<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfwk4ub9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfwk4ub9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-fill-round" /></template>
