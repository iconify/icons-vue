<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saj7vdbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="saj7vdbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:volleyball-ball-solid" /></template>
