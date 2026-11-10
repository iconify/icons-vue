<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou38wj13w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou38wj13w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-exclamation-point-filled" /></template>
