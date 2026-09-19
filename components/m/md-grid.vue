<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el3ty7ptn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="el3ty7ptn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-grid" /></template>
