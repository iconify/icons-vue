<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsotq7b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsotq7b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:starz" /></template>
