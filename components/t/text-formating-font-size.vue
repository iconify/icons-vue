<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-krc8bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-krc8bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:text-formating-font-size" /></template>
