<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja39s95eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ja39s95eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:upload-2" /></template>
