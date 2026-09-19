<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxj0m6wlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pxj0m6wlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:supabase-wordmark" /></template>
