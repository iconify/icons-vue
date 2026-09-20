<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2u_5ebdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k2u_5ebdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:raised-curb-with-arrow-down" /></template>
