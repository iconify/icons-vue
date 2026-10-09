<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_kyy_bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b_kyy_bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:noodles-48" /></template>
