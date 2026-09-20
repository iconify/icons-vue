<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxm_88f5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fxm_88f5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-vertical-stairs-ascend-up" /></template>
