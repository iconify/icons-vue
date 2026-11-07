<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk6ovimpe.css';
import '../../css/g/g9tggne-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk6ovimpe"/><path class="g9tggne-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quote-bold-duotone" /></template>
