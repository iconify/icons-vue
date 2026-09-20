<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6e8frbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6e8frbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-up-fill" /></template>
