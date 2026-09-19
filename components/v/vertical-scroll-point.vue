<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hry4lbbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hry4lbbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:vertical-scroll-point" /></template>
