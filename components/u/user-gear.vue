<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvs4s8b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bvs4s8b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:user-gear" /></template>
