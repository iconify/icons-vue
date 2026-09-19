<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig8s2roze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ig8s2roze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:underline-20-solid" /></template>
