<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_lt4yb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="k_lt4yb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:refreshalt" /></template>
