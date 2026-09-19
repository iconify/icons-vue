<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrks_obiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":718,"height":717};
const content = `<path class="wrks_obiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:move" /></template>
