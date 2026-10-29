<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq8mqkgzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq8mqkgzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:star-solid" /></template>
