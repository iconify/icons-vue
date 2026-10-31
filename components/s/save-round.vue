<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryt39u2qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryt39u2qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-round" /></template>
