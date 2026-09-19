<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc25grbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":488};
const content = `<path class="bc25grbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:smugmug" /></template>
