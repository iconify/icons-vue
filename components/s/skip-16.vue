<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvc7fdb5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uvc7fdb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:skip-16" /></template>
