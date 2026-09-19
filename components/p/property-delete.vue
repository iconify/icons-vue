<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq9x2sb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq9x2sb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:property-delete" /></template>
