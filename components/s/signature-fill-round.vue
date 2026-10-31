<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud-p4abac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud-p4abac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signature-fill-round" /></template>
