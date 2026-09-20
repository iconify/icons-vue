<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqy_hqb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jqy_hqb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:snowboarding" /></template>
