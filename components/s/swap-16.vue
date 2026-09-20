<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0vu_ab6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z0vu_ab6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:swap-16" /></template>
