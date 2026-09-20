<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1so0ab6o.css';
import '../../css/p/p1-cd6b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1so0ab6o"/><path class="p1-cd6b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:star-half-alt" /></template>
