<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_vt4xbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e_vt4xbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:sign-intersection-side-fill" /></template>
