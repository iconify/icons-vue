<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuhnlh07d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xuhnlh07d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:picture-outline" /></template>
