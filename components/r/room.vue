<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f89bh-bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f89bh-bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:room" /></template>
