<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/likabwbon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="likabwbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:phone" /></template>
