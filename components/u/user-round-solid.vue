<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2182vpgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2182vpgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-round-solid" /></template>
