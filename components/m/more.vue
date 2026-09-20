<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uleb8w86q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uleb8w86q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:more" /></template>
