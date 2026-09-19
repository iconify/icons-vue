<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq_l1x1ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="aq_l1x1ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:plus-circle" /></template>
