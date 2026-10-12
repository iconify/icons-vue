<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft7o93brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft7o93brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:volume-filled" /></template>
