<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zruphcbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zruphcbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:section-line" /></template>
