<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijq4veb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ijq4veb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:shield-exclamation-16-solid" /></template>
