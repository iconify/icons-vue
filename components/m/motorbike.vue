<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb93mzmbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb93mzmbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:motorbike" /></template>
