<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haz8azb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="haz8azb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speedometer-middle-outline" /></template>
