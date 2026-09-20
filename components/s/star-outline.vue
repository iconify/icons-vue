<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh5g9vpdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xh5g9vpdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:star-outline" /></template>
