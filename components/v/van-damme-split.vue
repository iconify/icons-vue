<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxnxazn8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxnxazn8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:van-damme-split" /></template>
