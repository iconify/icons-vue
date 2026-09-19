<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-oenbbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w-oenbbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:question-mark-circle-20-solid" /></template>
