<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3t4qwbjm.css';
import '../../css/b/b5_gm_r9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3t4qwbjm"/><path class="b5_gm_r9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:podcasts" /></template>
