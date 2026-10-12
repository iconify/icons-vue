<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3f72bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3f72bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:motorbike-filled" /></template>
