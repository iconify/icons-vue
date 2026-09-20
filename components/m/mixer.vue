<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5gdi-u-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5gdi-u-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mixer" /></template>
