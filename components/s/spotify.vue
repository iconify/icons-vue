<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo36hkleo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xo36hkleo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:spotify" /></template>
