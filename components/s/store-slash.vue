<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vopjp-b_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vopjp-b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:store-slash" /></template>
