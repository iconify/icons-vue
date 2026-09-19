<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx0608zwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zx0608zwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:shield-alt" /></template>
