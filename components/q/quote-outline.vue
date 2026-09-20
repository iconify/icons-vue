<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvwyqrblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mvwyqrblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:quote-outline" /></template>
