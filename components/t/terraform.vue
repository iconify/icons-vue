<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsk9_xzju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":72};
const content = `<path class="xsk9_xzju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:terraform" /></template>
