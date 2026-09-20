<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvtxr9b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvtxr9b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:step-backward-circle" /></template>
