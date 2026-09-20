<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agm10xb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="agm10xb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:smoking-area-remix" /></template>
