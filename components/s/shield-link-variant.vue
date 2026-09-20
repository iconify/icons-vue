<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe1qa4bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe1qa4bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-link-variant" /></template>
