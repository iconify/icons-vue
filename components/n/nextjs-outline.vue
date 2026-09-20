<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khr67rxkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="khr67rxkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:nextjs-outline" /></template>
