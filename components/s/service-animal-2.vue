<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao1b5d6rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao1b5d6rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:service-animal-2" /></template>
