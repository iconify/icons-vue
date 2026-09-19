<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmh1vd_lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmh1vd_lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:notebook" /></template>
