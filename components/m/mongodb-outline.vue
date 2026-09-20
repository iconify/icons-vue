<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ienuj02sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ienuj02sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mongodb-outline" /></template>
