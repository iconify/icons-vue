<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bna30gm7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bna30gm7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-octagon-filled" /></template>
