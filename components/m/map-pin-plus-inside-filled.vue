<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1h1xacii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1h1xacii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-plus-inside-filled" /></template>
