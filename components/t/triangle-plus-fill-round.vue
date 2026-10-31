<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6eap6brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6eap6brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-plus-fill-round" /></template>
