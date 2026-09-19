<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfkeo8igu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wfkeo8igu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:stop-20-solid" /></template>
