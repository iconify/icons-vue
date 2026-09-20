<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/der0l86hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="der0l86hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun" /></template>
