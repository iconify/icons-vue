<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfzz9-bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cfzz9-bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:wordpress" /></template>
