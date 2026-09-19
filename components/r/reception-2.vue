<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd835obmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nd835obmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:reception-2" /></template>
