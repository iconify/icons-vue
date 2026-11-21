<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8xwu9g6i.css';
import '../../css/q/qs9rc4bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="s8xwu9g6i"/><path class="qs9rc4bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:phone-portrait-outline" /></template>
