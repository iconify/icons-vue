<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llh11yb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="llh11yb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:svelte" /></template>
