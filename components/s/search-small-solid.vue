<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j59tpjvbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j59tpjvbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:search-small-solid" /></template>
