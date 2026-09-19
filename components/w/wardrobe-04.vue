<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5np71b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5np71b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wardrobe-04" /></template>
