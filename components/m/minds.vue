<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdw-y-o3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdw-y-o3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:minds" /></template>
