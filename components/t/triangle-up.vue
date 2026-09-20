<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4oeq0bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j4oeq0bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:triangle-up" /></template>
