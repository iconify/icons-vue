<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1-vf5x4j.css';
import '../../css/m/mzcm9qfhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d1-vf5x4j"/><path class="mzcm9qfhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wand-sparkles-filled" /></template>
