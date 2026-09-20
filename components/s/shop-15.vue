<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kad0u6noq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kad0u6noq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:shop-15" /></template>
