<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0k0o1c2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="k0k0o1c2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-301" /></template>
