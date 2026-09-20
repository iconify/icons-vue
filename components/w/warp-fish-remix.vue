<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpoq-6_vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kpoq-6_vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:warp-fish-remix" /></template>
