<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w91vljqod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w91vljqod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outdoor-motion" /></template>
