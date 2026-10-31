<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhi3rlo9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhi3rlo9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-3-fill-round" /></template>
