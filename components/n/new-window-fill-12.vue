<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3k1-4h4j.css';
import '../../css/k/k0n5xoqvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="b3k1-4h4j"/><path class="k0n5xoqvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:new-window-fill-12" /></template>
