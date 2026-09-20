<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6b1jqbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6b1jqbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:presentation-projector-1-bold" /></template>
