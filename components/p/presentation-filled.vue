<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff17ze2qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff17ze2qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:presentation-filled" /></template>
