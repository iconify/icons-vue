<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1rw8bc3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x1rw8bc3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:pager" /></template>
