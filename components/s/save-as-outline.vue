<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pia9tjb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pia9tjb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:save-as-outline" /></template>
