<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuebe5bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iuebe5bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pawprint" /></template>
