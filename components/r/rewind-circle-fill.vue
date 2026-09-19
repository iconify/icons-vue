<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lizjtjbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lizjtjbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:rewind-circle-fill" /></template>
