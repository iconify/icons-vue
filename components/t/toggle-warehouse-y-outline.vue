<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5muy2b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b5muy2b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:toggle-warehouse-y-outline" /></template>
