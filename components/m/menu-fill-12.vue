<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzy1_7bxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mzy1_7bxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:menu-fill-12" /></template>
