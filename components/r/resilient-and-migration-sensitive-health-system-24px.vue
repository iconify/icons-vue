<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2zfnvgut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2zfnvgut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:resilient-and-migration-sensitive-health-system-24px" /></template>
