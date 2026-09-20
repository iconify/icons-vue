<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6you7bfh.css';
import '../../css/i/icgyn9bub.css';
import '../../css/p/pzuqi_b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6you7bfh"/><path clip-rule="evenodd" class="icgyn9bub"/><path class="pzuqi_b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smart-watch-circle" /></template>
