<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bda7mub-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bda7mub-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:path" /></template>
