<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3fi1ehfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3fi1ehfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:smile-slight-fill-16" /></template>
