<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkncgtb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkncgtb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:smug-mug-logo" /></template>
