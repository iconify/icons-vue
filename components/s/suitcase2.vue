<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7b1f6mac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h7b1f6mac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:suitcase2" /></template>
