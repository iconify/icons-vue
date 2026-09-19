<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsyd9_bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lsyd9_bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:menu-alt-2" /></template>
