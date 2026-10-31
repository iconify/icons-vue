<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myjix-b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myjix-b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sort-a-z-duocolor-round" /></template>
