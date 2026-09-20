<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmz1f45_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmz1f45_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-quilt-outline" /></template>
