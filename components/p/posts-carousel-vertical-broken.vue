<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rct29b3qg.css';
import '../../css/e/ezkmwabnq.css';
import '../../css/j/janxgzbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rct29b3qg"/><path class="ezkmwabnq"/><path class="janxgzbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-vertical-broken" /></template>
