<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn9atv0gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn9atv0gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:scarf" /></template>
