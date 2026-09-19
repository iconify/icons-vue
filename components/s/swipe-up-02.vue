<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lml0hibhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lml0hibhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swipe-up-02" /></template>
