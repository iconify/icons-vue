<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mye_r2blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mye_r2blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:plus-circle-fill" /></template>
