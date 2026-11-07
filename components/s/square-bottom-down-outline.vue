<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3cwxfump.css';
import '../../css/k/ksuq6mb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3cwxfump"/><path class="ksuq6mb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-bottom-down-outline" /></template>
