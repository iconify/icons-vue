<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz0vkbces.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bz0vkbces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wallet-16-solid" /></template>
