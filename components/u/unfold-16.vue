<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/futdkq_zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="futdkq_zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unfold-16" /></template>
