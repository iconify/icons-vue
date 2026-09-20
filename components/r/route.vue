<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa5sfhb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fa5sfhb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:route" /></template>
