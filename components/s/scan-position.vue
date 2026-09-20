<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbvhxf02i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbvhxf02i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scan-position" /></template>
