<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbo3gpfgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbo3gpfgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-off-filled" /></template>
