<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8kk785yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y8kk785yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:netlify-solid" /></template>
