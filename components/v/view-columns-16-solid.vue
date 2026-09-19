<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lksonub4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lksonub4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:view-columns-16-solid" /></template>
