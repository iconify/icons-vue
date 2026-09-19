<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxs3ovoyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxs3ovoyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-left-01" /></template>
