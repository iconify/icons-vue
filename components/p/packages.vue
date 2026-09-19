<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4w3txb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4w3txb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:packages" /></template>
