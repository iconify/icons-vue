<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4-i83b6x.css';
import '../../css/c/c8yw7loqa.css';
import '../../css/y/yi_r72bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4-i83b6x"/><path class="c8yw7loqa"/><path class="yi_r72bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:wrap-text" /></template>
