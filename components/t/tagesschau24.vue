<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doq3m8b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doq3m8b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tagesschau24" /></template>
