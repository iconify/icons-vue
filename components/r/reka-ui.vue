<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlgo_mb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgo_mb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:reka-ui" /></template>
