<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9ejojb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t9ejojb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nine-point-star-outline" /></template>
