<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg97db8xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg97db8xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:package-process-01" /></template>
