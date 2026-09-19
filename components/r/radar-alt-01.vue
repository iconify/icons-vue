<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laz9y4bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="laz9y4bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:radar-alt-01" /></template>
