<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shfq65bhq.css';
import '../../css/p/puz5jibvr.css';
import '../../css/p/pjw9-5bis.css';
import '../../css/v/vvpeo-3dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="shfq65bhq"/><path class="puz5jibvr"/><path class="pjw9-5bis"/><path class="vvpeo-3dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-plus-20" /></template>
