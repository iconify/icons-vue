<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys0mczbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys0mczbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:table-cells-merge-filled" /></template>
