<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyffxu8qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyffxu8qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-x" /></template>
