<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kobx8zbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kobx8zbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-two-tone" /></template>
