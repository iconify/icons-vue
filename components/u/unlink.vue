<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9-e7g7ml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="l9-e7g7ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:unlink" /></template>
