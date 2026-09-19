<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbe08qa1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bbe08qa1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:star-half" /></template>
