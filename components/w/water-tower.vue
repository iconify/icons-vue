<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaz2klblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eaz2klblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:water-tower" /></template>
