<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do_oleb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="do_oleb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:square-fill-16" /></template>
