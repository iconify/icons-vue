<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg9ihxbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zg9ihxbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:paste-outline" /></template>
