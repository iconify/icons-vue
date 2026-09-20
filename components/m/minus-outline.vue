<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu7a8ewfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eu7a8ewfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minus-outline" /></template>
