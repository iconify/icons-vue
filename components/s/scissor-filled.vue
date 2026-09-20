<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x93rnabxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x93rnabxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scissor-filled" /></template>
