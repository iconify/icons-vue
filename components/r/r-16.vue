<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq195u44k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eq195u44k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:r-16" /></template>
