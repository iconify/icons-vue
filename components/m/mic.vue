<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsxk0_bpo.css';
import '../../css/u/usq2d7duw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="dsxk0_bpo"/><path class="usq2d7duw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mic" /></template>
