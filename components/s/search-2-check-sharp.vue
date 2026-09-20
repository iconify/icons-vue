<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5urce02d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5urce02d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-2-check-sharp" /></template>
