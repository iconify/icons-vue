<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfrct_bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bfrct_bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:rail-light-15" /></template>
