<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3cbd4b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c3cbd4b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:weixin-cards-offers" /></template>
