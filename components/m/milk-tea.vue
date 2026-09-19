<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4gf1vpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wt4gf1vpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:milk-tea" /></template>
