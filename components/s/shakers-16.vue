<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7j-npjlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r7j-npjlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:shakers-16" /></template>
