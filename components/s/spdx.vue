<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvzle9bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zvzle9bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:spdx" /></template>
