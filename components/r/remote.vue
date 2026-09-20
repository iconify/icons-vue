<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lri53bb8z.css';
import '../../css/d/dj1p29vfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lri53bb8z"/><path class="dj1p29vfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:remote" /></template>
