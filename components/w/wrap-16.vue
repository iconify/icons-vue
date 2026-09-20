<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obinhcsce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="obinhcsce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:wrap-16" /></template>
