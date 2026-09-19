<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln6oktiqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ln6oktiqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:mouse3" /></template>
