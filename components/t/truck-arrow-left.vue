<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8a-nzbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8a-nzbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-arrow-left" /></template>
