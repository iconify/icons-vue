<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgvi4xbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgvi4xbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:phone" /></template>
