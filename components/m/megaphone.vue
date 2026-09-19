<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zskw_mbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zskw_mbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:megaphone" /></template>
