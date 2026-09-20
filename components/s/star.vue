<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q85hjbrzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q85hjbrzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:star" /></template>
