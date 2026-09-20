<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx3ur7rfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx3ur7rfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:tab-text" /></template>
