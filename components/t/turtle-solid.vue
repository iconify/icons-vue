<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl1deib-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl1deib-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:turtle-solid" /></template>
