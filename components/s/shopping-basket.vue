<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ho1og4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="b2ho1og4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:shopping-basket" /></template>
