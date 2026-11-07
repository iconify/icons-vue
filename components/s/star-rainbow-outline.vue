<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er7-pbg8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er7-pbg8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-rainbow-outline" /></template>
