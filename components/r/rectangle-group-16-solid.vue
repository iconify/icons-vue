<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as8c1x0lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="as8c1x0lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:rectangle-group-16-solid" /></template>
