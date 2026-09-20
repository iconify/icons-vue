<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqxwy99bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oqxwy99bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:stack-16" /></template>
