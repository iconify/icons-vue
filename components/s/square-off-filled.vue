<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt_jtyb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt_jtyb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-off-filled" /></template>
