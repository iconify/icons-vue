<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_1zkkb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p_1zkkb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:play-forward-outline" /></template>
