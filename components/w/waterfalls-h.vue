<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3sqil9-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s3sqil9-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:waterfalls-h" /></template>
