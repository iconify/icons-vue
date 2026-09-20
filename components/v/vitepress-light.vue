<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv7g_mxtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lv7g_mxtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vitepress-light" /></template>
