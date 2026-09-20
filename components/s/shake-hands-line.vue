<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omt6qbbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omt6qbbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shake-hands-line" /></template>
