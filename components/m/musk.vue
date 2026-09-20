<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx3lc4baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xx3lc4baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:musk" /></template>
