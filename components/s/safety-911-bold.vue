<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp4irbc5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp4irbc5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:safety-911-bold" /></template>
