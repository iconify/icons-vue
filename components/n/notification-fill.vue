<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvpax_baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvpax_baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-fill" /></template>
