<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3gewezer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u3gewezer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nine-point-star" /></template>
