<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzpr2g3su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzpr2g3su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:parent-and-infant-priority-seating" /></template>
