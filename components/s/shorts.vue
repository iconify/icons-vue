<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfnsh61-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfnsh61-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:shorts" /></template>
