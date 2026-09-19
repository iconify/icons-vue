<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfxd2tr0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="bfxd2tr0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:weixin" /></template>
