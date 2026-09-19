<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzt41kbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pzt41kbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-follow-fill-12" /></template>
