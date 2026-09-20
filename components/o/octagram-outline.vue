<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byl-2r2kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byl-2r2kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:octagram-outline" /></template>
