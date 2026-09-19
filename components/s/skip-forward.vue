<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvzc1fbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bvzc1fbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:skip-forward" /></template>
