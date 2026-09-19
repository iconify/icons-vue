<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt9eu9bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bt9eu9bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:record" /></template>
