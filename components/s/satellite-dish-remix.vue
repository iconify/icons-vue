<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q21k9_bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q21k9_bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:satellite-dish-remix" /></template>
