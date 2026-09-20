<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjtwddpqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cjtwddpqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:zoom" /></template>
