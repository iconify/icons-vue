<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr7b1pcrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fr7b1pcrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stack-overflow" /></template>
