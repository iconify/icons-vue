<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh3w2t_7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bh3w2t_7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tree-growth" /></template>
