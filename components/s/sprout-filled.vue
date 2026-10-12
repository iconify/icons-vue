<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwxtb_fhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwxtb_fhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sprout-filled" /></template>
