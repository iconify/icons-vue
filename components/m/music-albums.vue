<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czmczs_ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="czmczs_ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:music-albums" /></template>
