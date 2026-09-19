<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7ozbv1eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a7ozbv1eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:park-bench" /></template>
