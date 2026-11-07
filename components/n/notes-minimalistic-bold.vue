<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szsyyvgyx.css';
import '../../css/e/e_dihi53c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szsyyvgyx"/><path class="e_dihi53c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:notes-minimalistic-bold" /></template>
