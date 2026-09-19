<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzba4of-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzba4of-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:prosthetic-leg" /></template>
