<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt1f5_b9q.css';
import '../../css/n/nvh489vpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt1f5_b9q"/><path clip-rule="evenodd" class="nvh489vpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shield-cog-filled" /></template>
