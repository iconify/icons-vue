<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2i_l0snn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="x2i_l0snn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sort" /></template>
