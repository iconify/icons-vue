<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ian07eb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ian07eb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:queue-list-20-solid" /></template>
