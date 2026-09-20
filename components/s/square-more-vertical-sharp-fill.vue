<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2q3aujem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2q3aujem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-more-vertical-sharp-fill" /></template>
