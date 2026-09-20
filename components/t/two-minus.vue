<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziiaqvbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ziiaqvbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:two-minus" /></template>
