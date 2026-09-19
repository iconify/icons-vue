<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z61ng_bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z61ng_bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rectangle-horizontal" /></template>
