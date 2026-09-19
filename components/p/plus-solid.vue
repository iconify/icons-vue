<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm7t0fbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dm7t0fbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:plus-solid" /></template>
