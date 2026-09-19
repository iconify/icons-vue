<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6e4u0b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b6e4u0b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:signal-slash-20-solid" /></template>
