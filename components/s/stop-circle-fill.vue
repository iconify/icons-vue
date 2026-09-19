<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_uvs0b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c_uvs0b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:stop-circle-fill" /></template>
