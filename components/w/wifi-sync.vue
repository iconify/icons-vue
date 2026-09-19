<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkxbe4bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkxbe4bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-sync" /></template>
