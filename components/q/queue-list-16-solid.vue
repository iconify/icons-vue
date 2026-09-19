<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuvcv35gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fuvcv35gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:queue-list-16-solid" /></template>
