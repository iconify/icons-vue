<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7xdvfbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7xdvfbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:square-rounded" /></template>
