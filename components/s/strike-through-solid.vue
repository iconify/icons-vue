<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei26nj97c.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei26nj97c"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:strike-through-solid" /></template>
