<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8xwu9g6i.css';
import '../../css/s/stdxmbcpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect transform="rotate(-90 256 256)" class="s8xwu9g6i"/><path class="stdxmbcpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:phone-landscape-outline" /></template>
