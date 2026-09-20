<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm-s8t0ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zm-s8t0ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:organization" /></template>
