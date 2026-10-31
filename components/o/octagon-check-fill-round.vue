<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxt3a99fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxt3a99fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-check-fill-round" /></template>
