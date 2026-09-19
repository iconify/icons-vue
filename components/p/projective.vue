<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syj7luboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="syj7luboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:projective" /></template>
