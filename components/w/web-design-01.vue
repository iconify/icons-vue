<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe7l5qbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe7l5qbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:web-design-01" /></template>
