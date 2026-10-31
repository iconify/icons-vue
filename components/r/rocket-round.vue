<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eghrht6fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eghrht6fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocket-round" /></template>
