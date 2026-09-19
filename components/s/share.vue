<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l11k1yqcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l11k1yqcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:share" /></template>
