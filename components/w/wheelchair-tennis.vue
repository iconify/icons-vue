<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtaeff6hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtaeff6hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wheelchair-tennis" /></template>
