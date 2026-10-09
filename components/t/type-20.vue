<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d17mx3bfs.css';
import '../../css/z/zr5giubst.css';
import '../../css/z/z01z8_btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d17mx3bfs"/><path class="zr5giubst"/><path class="z01z8_btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:type-20" /></template>
