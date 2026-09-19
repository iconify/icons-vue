<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arc_rcc5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arc_rcc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:test-tubes" /></template>
