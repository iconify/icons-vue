<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i106bb_zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i106bb_zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-rupee" /></template>
