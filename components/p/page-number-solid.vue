<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2b3d_yuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="l2b3d_yuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:page-number-solid" /></template>
