<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq8nqq2ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oq8nqq2ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shop" /></template>
