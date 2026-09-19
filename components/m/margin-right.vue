<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl76ilbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl76ilbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:margin-right" /></template>
