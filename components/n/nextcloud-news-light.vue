<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbuagsjxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wbuagsjxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-news-light" /></template>
