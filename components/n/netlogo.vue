<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei7bin-rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ei7bin-rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:netlogo" /></template>
