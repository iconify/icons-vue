<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zur5ywbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zur5ywbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:verified" /></template>
