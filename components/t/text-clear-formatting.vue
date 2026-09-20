<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr4-vob_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr4-vob_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-clear-formatting" /></template>
