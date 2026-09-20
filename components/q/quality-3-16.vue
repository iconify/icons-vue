<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz0qowrdw.css';
import '../../css/b/bc_xb1bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zz0qowrdw"/><path class="bc_xb1bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:quality-3-16" /></template>
