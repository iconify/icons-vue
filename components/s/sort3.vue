<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uya3rp9px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uya3rp9px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sort3" /></template>
