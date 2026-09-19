<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px64f9bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="px64f9bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:text" /></template>
