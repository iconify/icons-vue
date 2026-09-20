<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv74wh8fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv74wh8fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:paintbrush-2" /></template>
