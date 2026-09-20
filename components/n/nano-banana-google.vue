<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjm9s1b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjm9s1b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nano-banana-google" /></template>
