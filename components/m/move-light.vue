<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b21075lxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b21075lxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:move-light" /></template>
